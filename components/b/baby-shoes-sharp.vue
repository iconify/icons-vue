<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lu74_xb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-shoes-sharp" /></template>
<style>
.lu74_xb7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7.25v-1.5h8v6l6.5 2l2.015.712l-.015 2.138v3.15H3.75v-1.5Zm8 4.5l-2.5 3.75M3.75 17h16.5");
}

</style>
