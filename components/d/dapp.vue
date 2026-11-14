<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rxoq21bep"/><path class="ajz73bbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dapp" /></template>
<style>
.ajz73bbjm {
  d: path("M7.25 9.25h3.5v3.5h-3.5Zm6.25 0H17v3.5h-3.5ZM7.25 15.5h3.5V19h-3.5Zm6.25 0H17V19h-3.5Z");
}

.rxoq21bep {
  d: path("M2.5 2.5h19v19h-19Zm0 4h19");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
