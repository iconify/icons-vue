<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x1kjs4bnl"/><path class="bpfhkhbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:garden-scoop" /></template>
<style>
.bpfhkhbtr {
  d: path("M3 13c.5-6 6-9 10.5-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x1kjs4bnl {
  d: path("m3 13l10.5-7v7.5A5.5 5.5 0 0 1 8 19a5.5 5.5 0 0 1-5-6Zm10.5-4.5H20a1.75 1.75 0 0 1 0 3.5h-6.5");
}

</style>
