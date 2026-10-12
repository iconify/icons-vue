<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="vsa4owbaz"/><path class="e-a2-vbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autoplay" /></template>
<style>
.e-a2-vbpn {
  d: path("m15.08 9.89l2.59 1.72q.58.39 0 .78l-2.59 1.72q-.58.39-.58-.31v-3.6q0-.7.58-.31");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vsa4owbaz {
  width: 18.5px;
  height: 10.5px;
  x: 2.75px;
  y: 6.75px;
  rx: 5.25px;
}

</style>
