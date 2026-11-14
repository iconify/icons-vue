<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mmhsavwfa"/><path class="ajjav7b8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:angle" /></template>
<style>
.ajjav7b8m {
  d: path("M9.45 14.55a7 7 0 0 1 2.05 4.95");
}

.mmhsavwfa {
  d: path("m19 4.5l-14.5 15H20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
