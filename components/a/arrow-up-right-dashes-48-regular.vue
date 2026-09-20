<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kxk520m6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-right-dashes-48-regular" /></template>
<style>
.kxk520m6p {
  fill: currentColor;
  d: path("M22.25 6a1.25 1.25 0 1 0 0 2.5h15.482l-7.366 7.366a1.25 1.25 0 0 0 1.768 1.768l7.366-7.366V25.75a1.25 1.25 0 1 0 2.5 0V7.25C42 6.56 41.44 6 40.75 6zm-5.616 27.134a1.25 1.25 0 0 0-1.768-1.768l-8.5 8.5a1.25 1.25 0 0 0 1.768 1.768zm12-13.768a1.25 1.25 0 0 1 0 1.768l-8.5 8.5a1.25 1.25 0 0 1-1.768-1.768l8.5-8.5a1.25 1.25 0 0 1 1.768 0");
}

</style>
