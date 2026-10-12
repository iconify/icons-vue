<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-7ea3bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:comb-sharp" /></template>
<style>
.p-7ea3bok {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.25h18.5v4.5H2.75zM5 9.75v8.5m2.5-8.5v9.5m2.5-9.5v9.5m2.5-9.5v9.5m2.5-9.5v9.5m2.5-9.5v9.5m2.5-9.5v8.5");
}

</style>
