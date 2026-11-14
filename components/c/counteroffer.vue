<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zjkrodb6k"/><path class="vpljg9beo"/><path class="br6vtabco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:counteroffer" /></template>
<style>
.br6vtabco {
  d: path("m13.75 19.5l1.5 1.5l1.5-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vpljg9beo {
  d: path("M5.75 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm15 14v-4.25a2.75 2.75 0 0 0-5.5 0V21");
}

.zjkrodb6k {
  d: path("M9.913 19.413L3 12.5V3h9.5l8.5 8.5l-.692.692");
}

</style>
