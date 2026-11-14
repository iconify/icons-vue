<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ev-yx4boh"/><path class="isqhp5djo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cross-training" /></template>
<style>
.ev-yx4boh {
  d: path("m14.159 4.184l5.657 5.657l-2.475 2.475l-5.657-5.657Zm-8.38-1.056a3.75 3.75 0 1 1-2.651 2.651");
}

.isqhp5djo {
  d: path("m5.75 3.25l1 3.5l-3.5-1M4 20L14.5 9.5m-5 0L20 20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
