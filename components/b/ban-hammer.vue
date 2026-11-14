<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3ox0fak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ban-hammer" /></template>
<style>
.zi3ox0fak {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.354 4.818l2.828 2.828a2.5 2.5 0 0 1 0 3.536a2.5 2.5 0 0 1-3.536 0l-2.828-2.828a2.5 2.5 0 0 1 0-3.536a2.5 2.5 0 0 1 3.536 0M13.25 9.75L7.5 15.5m-2.5 3h8a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 20A1.5 1.5 0 0 1 5 18.5");
}

</style>
