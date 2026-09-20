<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kiupqtl0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-flow-square-multiple-20-filled" /></template>
<style>
.kiupqtl0r {
  fill: currentColor;
  d: path("M15.996 5.174A3 3 0 0 1 17.998 8v5a5 5 0 0 1-5 5h-5a3 3 0 0 1-2.826-2h6.824a4 4 0 0 0 4-4zM12 2a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V8.176q.239.072.5.074A1.75 1.75 0 0 0 4.176 7h.521c.96 0 1.855.48 2.387 1.277A3.87 3.87 0 0 0 10.303 10h.99l-1.647 1.646a.5.5 0 1 0 .707.707l2.5-2.5a.5.5 0 0 0 0-.707l-2.5-2.5a.5.5 0 1 0-.707.708L11.293 9h-.99a2.87 2.87 0 0 1-2.387-1.277A3.87 3.87 0 0 0 4.697 6h-.521a1.75 1.75 0 0 0-2.171-1.179A3 3 0 0 1 5 2zM2.5 5.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
