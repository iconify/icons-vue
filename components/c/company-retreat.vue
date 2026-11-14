<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0o6oubzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:company-retreat" /></template>
<style>
.u0o6oubzh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.154 16.829l3.413-5.513a1.75 1.75 0 0 1 2.944-.05l1.296 1.945a1.484 1.484 0 0 0 2.443.039a1.574 1.574 0 0 1 2.54-.03l2.61 3.48a1.75 1.75 0 0 1-1.4 2.8H5.642a1.75 1.75 0 0 1-1.488-2.671M15 5.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
