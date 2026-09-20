<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dsfo_sbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-48-filled" /></template>
<style>
.dsfo_sbvh {
  fill: currentColor;
  d: path("M4.366 4.366a1.25 1.25 0 0 1 1.768 0l37.5 37.5a1.25 1.25 0 0 1-1.768 1.768l-4.636-4.637A19.92 19.92 0 0 1 24 44C12.954 44 4 35.046 4 24c0-5.073 1.888-9.705 5.001-13.231L4.366 6.134a1.25 1.25 0 0 1 0-1.768M24 4c11.046 0 20 8.954 20 20c0 4.35-1.39 8.374-3.747 11.655L12.343 7.746A19.9 19.9 0 0 1 24 4");
}

</style>
