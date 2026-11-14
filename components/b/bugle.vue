<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pehfr6elc"/><path class="j8xreoxsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bugle" /></template>
<style>
.j8xreoxsg {
  d: path("M5 14a5 4.5 0 1 0 10 0a5 4.5 0 1 0-10 0ZM3 8v3");
}

.pehfr6elc {
  d: path("M3 9.5h11c3 0 5-1.75 7-3.5v7c-2-1.75-4-3.5-7-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
