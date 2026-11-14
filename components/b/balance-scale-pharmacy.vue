<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mwgtx3byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:balance-scale-pharmacy" /></template>
<style>
.mwgtx3byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7h15M12 4v16.5m-4 0h8M3 13a3 3 0 0 0 6 0Zm12 0a3 3 0 0 0 6 0ZM6 7l-3 6m3-6l3 6m9-6l-3 6m3-6l3 6");
}

</style>
