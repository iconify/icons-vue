<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z2cwnjw1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:auto-fit-width-32-light" /></template>
<style>
.z2cwnjw1w {
  fill: currentColor;
  d: path("M4.5 6a.5.5 0 0 1 .5.5v19a.5.5 0 0 1-1 0v-19a.5.5 0 0 1 .5-.5m23 0a.5.5 0 0 1 .5.5v19a.5.5 0 0 1-1 0v-19a.5.5 0 0 1 .5-.5m-7.853 4.647a.5.5 0 0 1 .707 0l4.5 4.5a.5.5 0 0 1 0 .707l-4.5 4.5a.5.5 0 1 1-.707-.707L23.293 16H8.707l3.146 3.146a.5.5 0 1 1-.707.707l-4-4a.5.5 0 0 1 0-.707l4-4a.5.5 0 1 1 .707.707L8.708 15h14.586l-3.646-3.646a.5.5 0 0 1 0-.707");
}

</style>
