<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g50uq2bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:check-in-sharp" /></template>
<style>
.g50uq2bfu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 8.25v-3h4.5v3m-7.75 0h11v12.5h-11zm3.5 3.5v5.5m4-5.5v5.5m4.75-3l2 2l4.25-4.5");
}

</style>
