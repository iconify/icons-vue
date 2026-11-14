<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fyxq-r3yg"/><path class="gp74vlbdw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:connecting-rod" /></template>
<style>
.fyxq-r3yg {
  d: path("M3 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm8 9.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

.gp74vlbdw {
  d: path("M5.25 6.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm8.5 9.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM9 9l3.5 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
