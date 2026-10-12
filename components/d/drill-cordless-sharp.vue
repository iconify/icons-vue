<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxcrfewzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drill-cordless-sharp" /></template>
<style>
.sxcrfewzz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 3.5h-10V10H7l.15 1.49l.45 4.27l.15 1.49h4.5l-.15-1.49l-.45-4.27L11.5 10h4.25V3.5zm1.5 1.25h3.5v4h-3.5zm3.5 2h2M4.5 17.25H15v4H4.5z");
}

</style>
