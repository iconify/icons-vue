<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-swg51e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cursor-plus" /></template>
<style>
.gr-swg51e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.41 7.71l10.18 4.08q1.16.46-.01.9l-3.66 1.37q-1.17.44-1.59 1.62l-1.41 3.89q-.42 1.18-.8-.01L8.63 8.44q-.38-1.19.78-.73m-4.66-.46h-2m4.5-2.5v-2m-2 2.5l-1.5-1.5");
}

</style>
