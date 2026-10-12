<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a6fdk_bmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bugle-sharp" /></template>
<style>
.a6fdk_bmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.75v2.5m0-1.25H15.5m-4.25 0a3 3 0 0 0 0-6h-3.5a3 3 0 0 0 0 6m7.75-.75c2.4-.25 4.1-1.5 5.1-3.05l.65-.7v9l-.65-.7c-1-1.55-2.7-2.8-5.1-3.05Z");
}

</style>
