<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="cvufeubyu"/><path class="q3d1u2b5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compare-properties" /></template>
<style>
.cvufeubyu {
  d: path("M2.5 10.5L6.25 5L10 10.5V20H2.5ZM14 4h7.5v16H14Zm-2-1.5v19");
}

.q3d1u2b5w {
  d: path("M4.75 20v-3.5h3V20m8.5-12.5h.01m2.99 0h.01M16.25 11h.01m2.99 0h.01m-3.01 9v-3.5h3V20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
