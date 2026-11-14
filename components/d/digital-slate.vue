<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c026rxbve"/><path class="db5ddc8se"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:digital-slate" /></template>
<style>
.c026rxbve {
  d: path("m2.686 4.016l17.902-1.881l.313 2.983L3 7ZM3 9.75h18V21H3Z");
}

.db5ddc8se {
  d: path("M7 13h10v4.75H7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
