<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frc0420rb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dust-storm-warning" /></template>
<style>
.frc0420rb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5H17m-14.5 5h12m-9.5 5h6.5m-9 5h9m9-15h.01M18 9.5h.01M18 14.75v3.5M18 21h.01");
}

</style>
