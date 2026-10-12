<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufq23ku-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:deploy-arrow-sharp" /></template>
<style>
.ufq23ku-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.25v-6.5M8.75 6L12 2.75L15.25 6m-12 5.5h17.5v9.75H3.25zm0 4.88h17.5M7 13.94h3m-3 4.87h3");
}

</style>
