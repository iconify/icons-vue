<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjxc4rbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:election-day-sharp" /></template>
<style>
.wjxc4rbqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11.75v9.5h14.5v-9.5Zm-2 0h18.5M9.5 16.5h5M9 11.75l1.66-7.82l6.36 1.35l-1.38 6.47");
}

</style>
