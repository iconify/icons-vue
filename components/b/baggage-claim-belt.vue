<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j124uacux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:baggage-claim-belt" /></template>
<style>
.j124uacux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14h16.5a1.25 1.25 0 0 1 1.25 1.25v4a1.25 1.25 0 0 1-1.25 1.25H3.75a1.25 1.25 0 0 1-1.25-1.25v-4A1.25 1.25 0 0 1 3.75 14ZM7 6.5h10V14H7Zm3 0v-2a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v2M6.5 17.25h.01m10.99 0h.01");
}

</style>
