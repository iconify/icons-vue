<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3xipdbpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cookware-set-sharp" /></template>
<style>
.x3xipdbpg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 6.75a4.25 2.25 0 0 1 8.5 0ZM9 4.5V2.75m-4.25 4h8.5v7h-8.5zm-2 10.5h12.5v4H2.75v-3.5Zm12.5 1h6");
}

</style>
