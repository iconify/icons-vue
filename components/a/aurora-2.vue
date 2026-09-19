<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="izui12b2l"/><rect class="jc1oydeao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aurora-2" /></template>
<style>
.izui12b2l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.8 27.327v-6.655h2.18c1.23 0 2.23 1 2.23 2.235s-1 2.235-2.23 2.235H18.8m2.18 0l2.179 2.183m7.623.002v-6.655h2.179c1.231 0 2.23 1 2.23 2.235s-.998 2.235-2.23 2.235h-2.179m2.18 0l2.179 2.183m-22.329-6.653v4.45a2.204 2.204 0 1 0 4.409 0v-4.45m-6.716 4.429H7.621m-.718 2.206l2.162-6.635l2.163 6.655m29.146-2.226h-2.883m-.718 2.206l2.162-6.635l2.163 6.655m-14.106 0a2.204 2.204 0 0 1-2.205-2.204v-2.246a2.204 2.204 0 1 1 4.41 0v2.246a2.204 2.204 0 0 1-2.205 2.204");
}

.jc1oydeao {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
