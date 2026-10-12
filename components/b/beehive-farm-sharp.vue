<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkpje_b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beehive-farm-sharp" /></template>
<style>
.pkpje_b8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4h18.5v3H2.75zm1.5 3h15.5v11.5H4.25zm0 5.75h15.5M10 16h4m-7.75 2.5v2.75m11.5-2.75v2.75");
}

</style>
