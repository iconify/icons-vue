<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l46gm38lo"/><rect transform="rotate(-20 24 24)" class="zw4jolb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:irma" /></template>
<style>
.l46gm38lo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.929 18.915v8.654m10.535-.01v-8.644l4.328 8.654l4.327-8.641v8.641m-16.789 0v-8.654h2.833a2.907 2.907 0 0 1 0 5.813H18.33m2.833 0l2.833 2.839m13.294-.024l3.149-8.628m1.535 5.759h-3.543");
}

.zw4jolb0i {
  width: 34.374px;
  height: 23.148px;
  x: 6.813px;
  y: 12.426px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
