<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl5qy2flv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cash-register-drawer" /></template>
<style>
.cl5qy2flv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5h9v4h-9Zm4.5 4v3M4.5 15L6 9.5h12l1.5 5.5m-17 0h19v6.5h-19ZM9 15v6.5m6-6.5v6.5");
}

</style>
