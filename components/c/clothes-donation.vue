<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uqghadbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:clothes-donation" /></template>
<style>
.uqghadbwr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 9.5L4 13h11.492m4.702-.452L21.5 9.5M4 13v7.5q0 .098.019.195t.057.188t.093.173q.054.081.124.151t.151.124q.082.055.173.093t.188.057T5 21.5h9.686M9.5 3l-3 1.5l1 2.75l1.5-.5V10h6V6.75l1.5.5l1-2.75l-3-1.5a2.5 2.5 0 0 1-5 0Zm9 18.5l-2.75-3a2 2 0 0 1 2.75-2.75a2 2 0 0 1 2.75 2.75Z");
}

</style>
