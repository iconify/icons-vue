<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fy_s8utaw"/><path class="m8pjzsbpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:desktop-calculator" /></template>
<style>
.fy_s8utaw {
  d: path("M4.5 4h15L21 20H3Z");
}

.m8pjzsbpf {
  d: path("M7.5 6.75h9v3h-9Zm0 6h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01m-9.01 4h.01m2.99 0h.01m2.99 0h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
