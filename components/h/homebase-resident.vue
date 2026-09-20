<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dqt6-6q3e"/><path class="qoao9ab1i"/><circle class="od44aeb_n"/><circle class="h-y2jnbuk"/><circle class="copcc2bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:homebase-resident" /></template>
<style>
.copcc2bxc {
  cx: 22.938px;
  cy: 27.969px;
  r: 0.75px;
  fill: currentColor;
}

.dqt6-6q3e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.513 3.434L7.934 10.696a6.98 6.98 0 0 0-3.487 6.042v14.525a6.98 6.98 0 0 0 3.487 6.04l12.579 7.263a6.98 6.98 0 0 0 6.974 0l12.579-7.263a6.98 6.98 0 0 0 3.487-6.04V16.737a6.98 6.98 0 0 0-3.487-6.04L27.487 3.433a6.98 6.98 0 0 0-6.974 0");
}

.h-y2jnbuk {
  cx: 22.938px;
  cy: 23.809px;
  r: 0.75px;
  fill: currentColor;
}

.od44aeb_n {
  cx: 22.938px;
  cy: 19.648px;
  r: 0.75px;
  fill: currentColor;
}

.qoao9ab1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.75 32.911l-.1-13.931a4.88 4.697 0 0 1 2.475-4.12l5.503-2.999a1.689 1.626 0 0 1 2.521 1.4l.122 13.387m3.667-8.419l2.194.943a4.253 4.113 0 0 1 2.523 3.898l-.117 3.334m-22.146-3.622l-2.688 1.327a4.614 4.462 0 0 0-2.517 4.033l.07 5.092m15.619-.205l4.485-2.968a4.302 4.14 0 0 1 4.772-.066l4.547 2.828");
}

</style>
