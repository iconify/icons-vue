<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eeuu98bgf"/><path class="q2tukqepe"/><path class="h02_xus3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cover-level-standard" /></template>
<style>
.eeuu98bgf {
  d: path("M3 15h4.25v6H3Z");
}

.h02_xus3y {
  d: path("M17 3.5h4.25V21H17Z");
}

.q2tukqepe {
  fill: currentColor;
  d: path("M10 9.5h4.25V21H10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
