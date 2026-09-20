<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xad7vzb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-48-regular" /></template>
<style>
.xad7vzb6x {
  fill: currentColor;
  d: path("M4.366 4.366a1.25 1.25 0 0 1 1.768 0l37.5 37.5a1.25 1.25 0 0 1-1.768 1.768l-4.636-4.637A19.92 19.92 0 0 1 24 44C12.954 44 4 35.046 4 24c0-5.073 1.888-9.705 5.001-13.231L4.366 6.134a1.25 1.25 0 0 1 0-1.768m6.407 8.174A17.43 17.43 0 0 0 6.5 24c0 9.665 7.835 17.5 17.5 17.5a17.43 17.43 0 0 0 11.458-4.274zM24 4c11.046 0 20 8.954 20 20c0 4.35-1.39 8.374-3.747 11.655l-1.795-1.795A17.4 17.4 0 0 0 41.5 24c0-9.665-7.835-17.5-17.5-17.5a17.4 17.4 0 0 0-9.861 3.041l-1.795-1.795A19.9 19.9 0 0 1 24 4");
}

</style>
