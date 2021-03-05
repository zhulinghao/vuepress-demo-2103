<template>
  <div>
    {{ zlhnb }}
  </div>
</template>
<script>
export default {
  data() {
    return {
      dynamicComponent: 1,
      zlhnb: '1111'
    }
  },
  mounted () {
    // import('./lib-that-access-window-on-import').then(module => {
    //   this.dynamicComponent = module.default
    // })
  }
}
</script>