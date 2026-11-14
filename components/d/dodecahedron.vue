<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="crsr5t9yn"/><path class="rpllbee4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dodecahedron" /></template>
<style>
.crsr5t9yn {
  d: path("m12.531 2.669l4.428 1.409a1.75 1.75 0 0 1 .878.629l2.822 3.83A1.75 1.75 0 0 1 21 9.575v4.85a1.75 1.75 0 0 1-.341 1.038l-2.822 3.83a1.75 1.75 0 0 1-.878.629l-4.428 1.409a1.75 1.75 0 0 1-1.062 0l-4.428-1.409a1.75 1.75 0 0 1-.878-.629l-2.822-3.83A1.75 1.75 0 0 1 3 14.425v-4.85a1.75 1.75 0 0 1 .341-1.038l2.822-3.83a1.75 1.75 0 0 1 .878-.629l4.428-1.409a1.75 1.75 0 0 1 1.062 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rpllbee4n {
  d: path("m12.865 8.111l2.515 1.775a1.5 1.5 0 0 1 .578 1.638l-.897 3.138a1.5 1.5 0 0 1-1.442 1.088h-3.238a1.5 1.5 0 0 1-1.442-1.088l-.897-3.138a1.5 1.5 0 0 1 .578-1.638l2.515-1.775a1.5 1.5 0 0 1 1.73 0M12 7.5v-5m4.25 8L21 9m-6.25 6.75l2.75 4m-8.25-4l-2.75 4m1.25-9.25L3 9");
}

</style>
