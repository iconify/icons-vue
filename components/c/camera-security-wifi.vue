<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-6dvibrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:camera-security-wifi" /></template>
<style>
.d-6dvibrx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.058 4.616l8.396 2.021a2.625 2.625 0 0 1 1.94 3.16l-.034.143a2.625 2.625 0 0 1-3.168 1.944L4.796 9.863a2.625 2.625 0 0 1-1.94-3.16l.034-.143a2.625 2.625 0 0 1 3.168-1.944m.192 5.634v5.25H3M3 13v5m13.5 1.25a2.5 2.5 0 0 1 3.5 0m-5.5-2a5.3 5.3 0 0 1 7.5 0");
}

</style>
