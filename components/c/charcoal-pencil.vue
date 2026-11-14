<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq9cwl5wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:charcoal-pencil" /></template>
<style>
.dq9cwl5wn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 16.75l10-10L20.5 3.5l-3.25 7.75l-10 10Zm10-10l4.5 4.5m.5-6.5l1.5 1.5");
}

</style>
