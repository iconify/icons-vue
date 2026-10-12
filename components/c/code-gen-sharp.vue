<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tf0dwscbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:code-gen-sharp" /></template>
<style>
.tf0dwscbl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 6.5L2.75 12L7 17.5m10-11l4.25 5.5L17 17.5M12 7.25q.57 4.18 4.75 4.75q-4.18.57-4.75 4.75q-.57-4.18-4.75-4.75q4.18-.57 4.75-4.75Z");
}

</style>
