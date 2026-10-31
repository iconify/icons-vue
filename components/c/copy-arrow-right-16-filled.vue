<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f8f6scbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-arrow-right-16-filled" /></template>
<style>
.f8f6scbrr {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M5 8.5c0 .966.392 1.841 1.025 2.475A5.48 5.48 0 0 0 7.257 15H3.5A2.5 2.5 0 0 1 1 12.5v-5A2.5 2.5 0 0 1 3.5 5H5zm6.854.646a.5.5 0 1 0-.707.708L12.293 11H9.5a.5.5 0 0 0 0 1h2.793l-1.146 1.146a.5.5 0 1 0 .707.707l2.002-2.001a.5.5 0 0 0-.002-.706zM12.5 1A2.5 2.5 0 0 1 15 3.5v3.757a5.502 5.502 0 0 0-8.696 2.438A2.5 2.5 0 0 1 6 8.5v-5A2.5 2.5 0 0 1 8.5 1z");
}

</style>
