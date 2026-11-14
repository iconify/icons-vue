<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="paylcdc7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-feed" /></template>
<style>
.paylcdc7z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 14c1.6-2.55 3.55-3.52 5.25-3.5c2.2-.02 3.83 1.6 4.5 3.5c-.67 2-2.3 3.63-4.5 3.75c-1.7-.12-3.65-1.1-5.25-3.75m-1.011-1.011l-.239-.239a.732.732 0 0 0-1.25.518v1.624a.718.718 0 0 0 1.25.483l.288-.317a1.5 1.5 0 0 0-.049-2.069M15.25 13h.01M8 4h.01M12 6h.01M16 4h.01");
}

</style>
