<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hf6-bzrlb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-32-filled" /></template>
<style>
.hf6-bzrlb {
  fill: currentColor;
  d: path("M4 9.25A3.25 3.25 0 0 1 7.25 6h17.5A3.25 3.25 0 0 1 28 9.25v9.5A3.25 3.25 0 0 1 24.75 22H7.25A3.25 3.25 0 0 1 4 18.75zM3 24a1 1 0 1 0 0 2h26a1 1 0 1 0 0-2z");
}

</style>
