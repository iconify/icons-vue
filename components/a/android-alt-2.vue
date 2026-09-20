<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="d90t1gbjt"/><path class="yd8jzx11m"/><circle class="nxzqkxyjc"/><circle class="kda1g59vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:android-alt-2" /></template>
<style>
.d90t1gbjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.786 21.225a1.6 1.6 0 0 1 1.67 1.34l.02 6.55c0 5.138-2.742 9.887-7.192 12.455c-6.873 3.97-15.663 1.618-19.634-5.254a14.37 14.37 0 0 1-1.927-7.297v-6.453a1.183 1.183 0 0 1 1.315-1.34");
}

.kda1g59vh {
  cx: 30.609px;
  cy: 15.531px;
  r: 2.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nxzqkxyjc {
  cx: 17.25px;
  cy: 15.531px;
  r: 2.153px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yd8jzx11m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.038 21.225h25.748a1.515 1.515 0 0 0 1.475-1.512v-1.9a11.6 11.6 0 0 0-2.685-7.291L37.59 8.53a2.394 2.394 0 0 0 0-3.326a2.32 2.32 0 0 0-3.334.006l-2.007 1.992c-5.448-3.468-11.002-3.73-16.734 0L13.583 5.24a2.29 2.29 0 0 0-3.338-.003c-1.434 1.244-.218 3.112-.004 3.323l2.007 1.976a11.22 11.22 0 0 0-2.723 7.276v1.9a1.51 1.51 0 0 0 1.507 1.513z");
}

</style>
