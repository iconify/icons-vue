<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9nk49b1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hair-dye-bowl" /></template>
<style>
.q9nk49b1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h17a8.5 8.5 0 0 1-17 0Zm7 0l4.75-4.75m2.457-4.578l2.121 2.121l-3.535 3.535l-2.121-2.121Z");
}

</style>
