<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jnrl10bsx"/><circle class="ff2w_2bef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:joint-knee" /></template>
<style>
.ff2w_2bef {
  cx: 19.75px;
  cy: 13px;
  r: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jnrl10bsx {
  d: path("M9.5 2.75h5v6C16 9 17 10 17 11.25v.25H7v-.25C7 10 8 9 9.5 8.75ZM7 14.5h10v.25c0 1.25-1 2.25-2.5 2.5v4h-5v-4C8 17 7 16 7 14.75Z");
}

</style>
