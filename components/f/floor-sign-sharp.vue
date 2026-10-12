<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-46_0bir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:floor-sign-sharp" /></template>
<style>
.v-46_0bir {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 3.75v16.5h3.5M19 3.75v16.5h-3.5M12 6.5V16m-2.75-2.75L12 16l2.75-2.75");
}

</style>
