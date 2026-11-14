<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="twlnv9bsa"/><path class="ojpqk-z_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cable-reel" /></template>
<style>
.ojpqk-z_b {
  d: path("M7 9a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 6.5V19H15m0-2.5h4.5v5H15Zm4.5 1H22m-2.5 3H22");
}

.twlnv9bsa {
  d: path("M3 9a6.5 6.5 0 1 0 13 0A6.5 6.5 0 1 0 3 9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
