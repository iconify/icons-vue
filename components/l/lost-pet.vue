<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q556nh62y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lost-pet" /></template>
<style>
.q556nh62y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 3H13c2.25 0 4 .75 4.25 2.75l.5 4c.25 2-2 2.5-2.5.75L14 6.25v5c0 3-1.75 5-3.75 5s-3.75-2-3.75-5v-5L5.25 10.5c-.5 1.75-2.75 1.25-2.5-.75l.5-4C3.5 3.75 5.25 3 7.5 3Zm1.25 5h.01m2.99 0h.01m-1.51 3.75h.01m8.24 10c-2-2-2.75-3.25-2.75-4.5a2.75 2.75 0 0 1 5.5 0c0 1.25-.75 2.5-2.75 4.5Zm0-4.5h.01");
}

</style>
