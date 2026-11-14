<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lbyp8cycv"/><path class="n6os-bs9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fly-fisher" /></template>
<style>
.lbyp8cycv {
  d: path("M4.25 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.n6os-bs9h {
  d: path("M6.5 7v8L4 21.5M6.5 15L9 21.5m-2.5-11l3-2l9.5-6m0 0c2.5 3.5 2.5 8.5.5 12M12 18q2.25-1.5 4.5 0t4.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
