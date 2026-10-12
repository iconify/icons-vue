<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fw7p_gbpg"/><path class="c3r_tjbam"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cheese-sharp" /></template>
<style>
.c3r_tjbam {
  d: path("M6.75 15.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0ZM13 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.fw7p_gbpg {
  d: path("m3.25 11.25l10-6.5l7.5 4v12.5H3.25v-2Zm0 0h17.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
