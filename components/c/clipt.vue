<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-_nm9h7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clipt" /></template>
<style>
.z-_nm9h7h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.391 43.5h-4.953c-6.96 0-12.603-5.643-12.603-12.603V18.364a3.78 3.78 0 0 1 3.78-3.781h12.687a3.78 3.78 0 0 1 3.78 3.78v11.35a3.78 3.78 0 0 1-3.78 3.78h-2.603a3.78 3.78 0 0 1-3.782-3.78V8.28a3.78 3.78 0 0 1 3.782-3.78h3.864c6.96 0 12.603 5.643 12.603 12.603v13.794");
}

</style>
