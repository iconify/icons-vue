<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v79ixej4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:auction-paddle-sharp" /></template>
<style>
.v79ixej4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.72 5.5l1.78-1.78l.88-.88l.88.88l6.02 6.02l.88.88l-.88.88l-1.78 1.78l-.88.88l-.88-.88l-6.02-6.02l-.88-.88zm2.78 5l-7.25 7.25m8.5 3h8.5");
}

</style>
