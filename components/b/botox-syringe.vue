<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kw1kpcb_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:botox-syringe" /></template>
<style>
.kw1kpcb_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.01 5.99l-2.121 2.121m-1.768-1.768l3.536 3.536m-3.005-3.006l2.475 2.475l-5.657 5.657l-2.475-2.475Zm-4.42 6.895l-2.121 2.121m-1.414-1.414l2.828 2.828M17.5 14.5c.25 2 1 2.75 3 3c-2 .25-2.75 1-3 3c-.25-2-1-2.75-3-3c2-.25 2.75-1 3-3Z");
}

</style>
