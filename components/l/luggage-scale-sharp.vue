<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="boioita6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:luggage-scale-sharp" /></template>
<style>
.boioita6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.75h4.5m-2.25 0v3m-2.75 0h5.5v5.5h-5.5zm2.75 2v1.5m0 2v3m-2.25 3v-3h4.5v3m-9.5 0h14.5v4H4.75z");
}

</style>
