<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wuelkb1dg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-badge" /></template>
<style>
.wuelkb1dg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.25l2.135 1.781l2.74-.475l.959 2.61l2.61.959l-.475 2.74L21.75 12l-1.781 2.135l.475 2.74l-2.61.959l-.959 2.61l-2.74-.475L12 21.75l-2.135-1.781l-2.74.475l-.959-2.61l-2.61-.959l.475-2.74L2.25 12l1.781-2.135l-.475-2.74l2.61-.959l.959-2.61l2.74.475ZM9.5 14.5l5-5m-4.75.25h.01m4.49 4.5h.01");
}

</style>
