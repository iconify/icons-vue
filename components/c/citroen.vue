<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="mbc5-pbdm"/><path class="xj46vxb9a"/><path class="fk2t6wttr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:citroen" /></template>
<style>
.fk2t6wttr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.794 33.808L24 23.23l14.206 10.576");
}

.mbc5-pbdm {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 16.177px;
  ry: 20.5px;
}

.xj46vxb9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.919 26.227L24 14.254l16.082 11.973");
}

</style>
