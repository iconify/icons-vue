<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q191h6b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-injector-sharp" /></template>
<style>
.q191h6b8c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 2.75h4.5v2.5h-4.5zM9 5.25h6.75V11l-.46.59l-1.58 2.07l-.46.59h-2.5l-.46-.59l-1.58-2.07l-.46-.59V5.25zM8.25 8.5h7.5M12 18.25v3m-3-3l-1.5 3m7.5-3l1.5 3");
}

</style>
