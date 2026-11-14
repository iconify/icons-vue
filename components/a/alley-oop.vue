<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lf0-u1c8y"/><path class="hdsckdb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:alley-oop" /></template>
<style>
.hdsckdb4f {
  d: path("M6.5 7h8M9 3.25c2.25 2.25 2.25 5.25 0 7.5M3 17.5h.01m.74-4.75h.01M13.5 15h8m-7 0l1.5 5.5h3l1.5-5.5");
}

.lf0-u1c8y {
  d: path("M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
