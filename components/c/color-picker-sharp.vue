<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1awoacbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:color-picker-sharp" /></template>
<style>
.w1awoacbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.66 4.75l-1.41-1.41l-.71-.71l-.71.71l-.7.7l-.71.71l.71.71l1.41 1.41l.71.71l.71-.71l.7-.7l.71-.71zm-2.83 1.42l-2.12 2.12m2.06 2.05l-4.11-4.11l-.42-.42l-.42.42l-.58.58l-.42.42l.43.42l.38.39l.43.42l-.42.42l-6.41 6.41l-.42.42l-.15.58l-.58 2.2l-.15.58l.58-.15l2.2-.58l.58-.15l.42-.42l6.41-6.41l.42-.42l.42.43l.39.38l.42.43l.42-.42l.58-.58l.42-.42z");
}

</style>
