<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="adeii4-2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:annotation-box-sharp" /></template>
<style>
.adeii4-2z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 4.5h9m-9 15h9m-12-12v9m15-9v9M2.75 2.75h3.5v3.5h-3.5zm15 0h3.5v3.5h-3.5zm-15 15h3.5v3.5h-3.5zm15 0h3.5v3.5h-3.5zm-9.5-7.5h7.5v3.5h-7.5z");
}

</style>
