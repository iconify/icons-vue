<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j00yyvb9p"/><path class="chvxh_b9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:avatar-3d" /></template>
<style>
.chvxh_b9d {
  d: path("M7 5.25L12 8l5-2.75M12 8v5.75");
}

.j00yyvb9p {
  d: path("m12 2.5l5 2.75V11l-5 2.75L7 11V5.25Zm-7.5 19c0-3 3.25-5 7.5-5s7.5 2 7.5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
