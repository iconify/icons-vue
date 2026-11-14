<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c36jdvbft"/><path class="g00izwb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ar-measure" /></template>
<style>
.c36jdvbft {
  d: path("m11.25 2.5l7 3.5v8l-7 3.5l-7-3.5V6Z");
}

.g00izwb9y {
  d: path("m4.25 6l7 3.5l7-3.5m-7 3.5v8m0 0L13 21m5.25-7L20 17.5M12.5 20l7-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
