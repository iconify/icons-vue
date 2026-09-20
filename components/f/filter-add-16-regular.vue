<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ejq8dybdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-add-16-regular" /></template>
<style>
.ejq8dybdf {
  fill: currentColor;
  d: path("M8.5 13a.5.5 0 0 1 0 1h-3a.5.5 0 0 1 0-1zM6.257 9c.313.38.677.716 1.08 1H3.5a.5.5 0 0 1 0-1zM10.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2a.5.5 0 0 0-.5.5V5H8.5a.5.5 0 0 0 0 1H10v1.5a.5.5 0 0 0 1 0V6h1.5a.5.5 0 0 0 0-1H11V3.5a.5.5 0 0 0-.5-.5M5.022 5a5.6 5.6 0 0 0 0 1H1.5a.5.5 0 0 1 0-1z");
}

</style>
