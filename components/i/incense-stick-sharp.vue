<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6uyx2mqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:incense-stick-sharp" /></template>
<style>
.k6uyx2mqh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.5 8.25l2.45-.817L16.5 5.5l-1.4-1.867l2.65-.883m1 7.75l1.842-.368L21 8.5M7.5 18.25L14.75 9m-12 9.25h18.5v3H2.75z");
}

</style>
