<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdgulnsgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alphabet-sharp" /></template>
<style>
.jdgulnsgt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 20.25l4.75-16l4.75 16m-7.75-5.5h6M15 4.25v16m0-3a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
