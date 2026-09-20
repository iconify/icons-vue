<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a-tbl0bst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-shift-16-regular" /></template>
<style>
.a-tbl0bst {
  fill: currentColor;
  d: path("M8.395 2.191a.504.504 0 0 0-.789 0l-4.6 5.802h2.482a.503.503 0 0 1 .502.5V13h4.02V8.494a.5.5 0 0 1 .503-.5h2.48zm-1.578-.62a1.51 1.51 0 0 1 2.367 0l4.598 5.802c.52.657.05 1.621-.789 1.621h-1.978V13c0 .553-.45 1.001-1.005 1.001H5.99A1.003 1.003 0 0 1 4.985 13V8.994H3.007c-.84 0-1.31-.965-.789-1.62z");
}

</style>
