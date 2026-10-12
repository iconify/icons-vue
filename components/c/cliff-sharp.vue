<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1fnzxire"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cliff-sharp" /></template>
<style>
.n1fnzxire {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.45V7l.79-.14l9.67-1.72L14 5l.61.51l.28.23l.61.51l-.36.72l-1.03 2.06l-.36.72l.27.75l.71 2l.27.75l-.32.74l-.86 2.02l-.32.74l.17.78l.66 2.94l.17.78H2.75zm2.75-6.2L11 13m6.25 2.75l1-.746l1 .746l1 .746l1-.746m-4 3.75l1-.746l1 .746l1 .746l1-.746");
}

</style>
