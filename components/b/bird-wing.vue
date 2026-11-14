<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pte88ubbn"/><path class="k_by7bbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bird-wing" /></template>
<style>
.k_by7bbdl {
  d: path("M16.5 11.5c-3.5 0-7-1.25-9.5-3.5m6 7c-2.5-.75-4.5-2.25-6-4");
}

.pte88ubbn {
  d: path("M3.5 4.5c6-.5 12.5.5 17 3.75c.5 1.5 0 2.75-1.5 3.25h-2.5c.75 1.25.5 2.75-1 3.5H13c.5 1.75 0 3.5-2 4.5C6.5 18 3.5 13 3.5 4.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
