<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y_an6vb8i"/><path class="tn-mz5b2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:beamed-notes" /></template>
<style>
.tn-mz5b2h {
  d: path("M9.75 18.5v-14l10-2v14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_an6vb8i {
  d: path("M4.25 18.5a2.75 2.25 0 1 0 5.5 0a2.75 2.25 0 1 0-5.5 0Zm10-2a2.75 2.25 0 1 0 5.5 0a2.75 2.25 0 1 0-5.5 0Z");
}

</style>
