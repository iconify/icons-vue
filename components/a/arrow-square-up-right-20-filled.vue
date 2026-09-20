<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xo86pybue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-square-up-right-20-filled" /></template>
<style>
.xo86pybue {
  fill: currentColor;
  d: path("M3 6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm9.691 1.038A.5.5 0 0 0 12.5 7h-5a.5.5 0 0 0 0 1h3.793l-4.147 4.146a.5.5 0 0 0 .708.708L12 8.707V12.5a.5.5 0 0 0 1 0v-5a.5.5 0 0 0-.144-.351l-.005-.005a.5.5 0 0 0-.16-.106");
}

</style>
