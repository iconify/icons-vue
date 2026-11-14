<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cl0ng5jis"/><path class="hxyc6eb3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:design-token-colour" /></template>
<style>
.cl0ng5jis {
  d: path("M12 3c5.5 0 9.5 4 9.5 8.5c0 3-2.5 4-4.5 3.5s-3.5 1-2.5 3s-.5 3-2.5 3c-5.5 0-9.5-4-9.5-9s4-9 9.5-9Z");
}

.hxyc6eb3l {
  d: path("m9 8l2.165 1.25v2.5L9 13l-2.165-1.25v-2.5Zm4 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
