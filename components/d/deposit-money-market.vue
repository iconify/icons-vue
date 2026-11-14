<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b4m00yb-m"/><path class="ov0fbgb5v"/><path class="du0yrjmns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-money-market" /></template>
<style>
.b4m00yb-m {
  d: path("M11.265 21H6.25q-.169.005-.337-.018q-.167-.023-.329-.074q-.161-.051-.311-.128q-.151-.077-.286-.179q-.136-.102-.252-.224t-.21-.264q-.095-.14-.164-.295T4.25 19.5l-1.75-7h9.9m6.2 0h1.2M5.5 8.25a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0Z");
}

.du0yrjmns {
  d: path("M12.25 8.25V10c0 .75 1.25 1.25 3 1.25s3-.5 3-1.25V8.25m-3.25 13L21.25 15m-7 .5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm5.25 5.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ov0fbgb5v {
  d: path("M5.5 8.25V10c0 .75 1.25 1.25 3 1.25s3-.5 3-1.25V8.25m.75 0a3 1.25 0 1 0 6 0a3 1.25 0 1 0-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
