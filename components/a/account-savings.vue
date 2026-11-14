<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cva0gw_7i"/><path class="oclckjclv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-savings" /></template>
<style>
.cva0gw_7i {
  d: path("M4 13.5c0-3.5 3.6-6 8-6s8 2.5 8 6c0 2.2-1.3 4-3.5 5V21H14v-1.75c-.65.15-1.3.25-2 .25s-1.35-.1-2-.25V21H7.5v-2.5c-2.2-1-3.5-2.8-3.5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oclckjclv {
  d: path("M4.5 12h-2v3h2m3.25-2.75h.01");
}

</style>
