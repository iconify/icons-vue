<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efpx_kbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-merge" /></template>
<style>
.efpx_kbxc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM2.5 18c0-3.75 2-6 4.5-6c1.5 0 2.75.5 3.5 1.5m2-3.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM10 21.5c0-3.25 2.5-5.25 6-5.25s6 2 6 5.25");
}

</style>
