<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pivwhss5n"/><path class="gvh3r1b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:elucid" /></template>
<style>
.gvh3r1b-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.895 27.534l13.823-6.59H16.895zm13.823-13.18l-13.823 6.59h13.823z");
}

.pivwhss5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.273 43.5h11.454m-13.311-4.643h15.168m-11.138-4.343H15.49c-4.624-2.854-7.707-7.962-7.707-13.797C7.783 11.762 15.044 4.5 24 4.5s16.217 7.262 16.217 16.217c0 5.835-3.083 10.943-7.707 13.797h-4.956");
}

</style>
