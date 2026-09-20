<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkkhx5dut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-circle-up-48-regular" /></template>
<style>
.gkkhx5dut {
  fill: currentColor;
  d: path("M15.366 24.134a1.25 1.25 0 0 0 1.768 0l5.616-5.616V32.75a1.25 1.25 0 1 0 2.5 0V18.518l5.616 5.616a1.25 1.25 0 0 0 1.768-1.768l-7.75-7.75a1.25 1.25 0 0 0-1.768 0l-7.75 7.75a1.25 1.25 0 0 0 0 1.768M4 24c0 11.046 8.954 20 20 20s20-8.954 20-20S35.046 4 24 4S4 12.954 4 24m20 17.5c-9.665 0-17.5-7.835-17.5-17.5S14.335 6.5 24 6.5S41.5 14.335 41.5 24S33.665 41.5 24 41.5");
}

</style>
