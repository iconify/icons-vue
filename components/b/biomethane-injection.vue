<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bzqzgwgrs"/><path class="vgmpjzj8o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:biomethane-injection" /></template>
<style>
.bzqzgwgrs {
  d: path("M11 21.5V12l5.25-5l5.25 5v9.5ZM2.5 14H11m-8.5 3H11M6 2.5C8.5 5 9 6.5 9 8a3 3 0 0 1-6 0c0-1.25.75-2.25 1.75-3C5 6 5.5 6.5 6 6.75C6 5.25 5.5 4 6 2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vgmpjzj8o {
  d: path("m13.75 13l2.5 2.5l-2.5 2.5");
}

</style>
