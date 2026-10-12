<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn951_64l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:director-chair-sharp" /></template>
<style>
.yn951_64l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 2.75h15.5v5H4.25zm1.5 5v4.5m12.5-4.5v4.5m-15 0h17.5m-14.5 0l11.5 9m0-9l-11.5 9");
}

</style>
