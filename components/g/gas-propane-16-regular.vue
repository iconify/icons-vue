<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="o7ix1bqtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gas-propane-16-regular" /></template>
<style>
.o7ix1bqtw {
  fill: currentColor;
  d: path("M11.5 1a.5.5 0 0 1 0 1H11v3.05a2.5 2.5 0 0 1 2 2.45v4a2.5 2.5 0 0 1-2.5 2.5h-5A2.5 2.5 0 0 1 3 11.5v-4a2.5 2.5 0 0 1 2-2.45V2h-.5a.5.5 0 0 1 0-1zM4 11.5A1.5 1.5 0 0 0 5.5 13h5a1.5 1.5 0 0 0 1.5-1.5V10H4zM5.5 6A1.5 1.5 0 0 0 4 7.5V9h8V7.5A1.5 1.5 0 0 0 10.5 6zM6 5h1.5V4a.5.5 0 0 1 0-1h1a.5.5 0 0 1 0 1v1H10V2H6z");
}

</style>
