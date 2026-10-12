<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="qrj-srblz"/><path class="znougq8ga"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cinder-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qrj-srblz {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 1.5px;
}

.znougq8ga {
  d: path("M6.75 10H9.5q.75 0 .75.75v2.5q0 .75-.75.75H6.75Q6 14 6 13.25v-2.5q0-.75.75-.75m7.75 0h2.75q.75 0 .75.75v2.5q0 .75-.75.75H14.5q-.75 0-.75-.75v-2.5q0-.75.75-.75");
}

</style>
