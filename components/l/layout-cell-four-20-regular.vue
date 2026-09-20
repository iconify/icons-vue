<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ubssb8bvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-cell-four-20-regular" /></template>
<style>
.ubssb8bvw {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm3-2a2 2 0 0 0-2 2v3.5h5.5V4zm3.5 6.5H4V14a2 2 0 0 0 2 2h3.5zm1 0V16H14a2 2 0 0 0 2-2v-3.5zm5.5-1V6a2 2 0 0 0-2-2h-3.5v5.5z");
}

</style>
