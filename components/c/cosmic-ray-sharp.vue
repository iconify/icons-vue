<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ia-bamxsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cosmic-ray-sharp" /></template>
<style>
.ia-bamxsk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 14A7.25 7.25 0 0 1 10 21.25H2.75ZM21 3L10.5 13.5m4 0h-4v-4m-5.9 2.6l.35-1.95m8 7.95l1.8-.8");
}

</style>
