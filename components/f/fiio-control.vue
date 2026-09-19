<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mh6-6mbtc"/><path class="zb846gbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fiio-control" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mh6-6mbtc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m19.955 28.121l8.09-8.044l-3.952-3.946v15.738l3.952-3.946l-8.09-8.044");
}

.zb846gbpm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.325 18.03s-2.348.302-3 1.1s-.61 2.356.757 3.996c.703.844 1.613.742 2.33.443c.676-.281 1.174-.63 1.06-1.494C37.53 14.922 31.41 9.402 24 9.402s-13.53 5.52-14.472 12.673c-.114.865.384 1.212 1.06 1.494c.717.299 1.627.401 2.33-.443c1.367-1.64 1.41-3.196.757-3.995s-3-1.101-3-1.101m26.943 11.24c-2.114 5.458-7.414 9.328-13.618 9.328s-11.504-3.87-13.618-9.327m0 0l2.599-2.864m.047 7.223l2.897-3.193");
}

</style>
