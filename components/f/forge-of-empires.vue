<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l25yi7a5e"/><path class="jg1qq6hpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:forge-of-empires" /></template>
<style>
.jg1qq6hpa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.732 13.695h3.971v18h-3.971z");
}

.l25yi7a5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 41.819c12.863-5.675 18.5-12.182 18.5-24.137V8.716h-6.734c-3.083 0-7.396.019-11.766-2.535c-4.37 2.554-8.682 2.535-11.766 2.535H5.5v8.966c0 11.955 5.637 18.462 18.5 24.137m-6.254-28.124h12.508m0 3.011v-3.011m-1.191 10.57v-4m-5.361 2h5.361m-11.317 9.43h8.272");
}

</style>
