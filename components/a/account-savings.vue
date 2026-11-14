<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j8zgdfb2n"/><path class="oclckjclv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-savings" /></template>
<style>
.j8zgdfb2n {
  d: path("M4 13.5c0-3.5 3.6-6 8-6s8 2.5 8 6c0 2.2-1.3 4-3.5 5V21H14v-1.75c-.65.15-1.3.25-2 .25s-1.35-.1-2-.25V21H7.5v-2.5c-2.2-1-3.5-2.8-3.5-5Z");
}

.oclckjclv {
  d: path("M4.5 12h-2v3h2m3.25-2.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
