<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t0yzzwb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-4-search-16-filled" /></template>
<style>
.t0yzzwb4a {
  fill: currentColor;
  d: path("M13.25 12a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1 0-1.5zm.541-1.734a.75.75 0 0 1-.541.234H2.75a.75.75 0 0 1 0-1.5h9.775zM10.5 1a3.5 3.5 0 0 1 2.946 5.386L15.78 8.72a.75.75 0 1 1-1.06 1.06l-2.334-2.334A3.5 3.5 0 1 1 10.5 1M6.256 6a4.5 4.5 0 0 0 .89 1.5H2.75a.75.75 0 0 1 0-1.5zM10.5 2.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4M6.256 3C6.09 3.47 6 3.974 6 4.5H2.75a.75.75 0 0 1 0-1.5z");
}

</style>
