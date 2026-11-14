<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loe80hwrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:leaf-blower" /></template>
<style>
.loe80hwrm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4h6v7.5h-6Zm6 2l5.5.75v2l-5.5.75ZM13 20.5c0-4 3-6.5 7.5-6.5c0 4-3 6.5-7.5 6.5Zm3.75-14.25h4.75m-4.75 3H20");
}

</style>
