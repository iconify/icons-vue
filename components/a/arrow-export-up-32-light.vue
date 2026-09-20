<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l8a9xbbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-up-32-light" /></template>
<style>
.l8a9xbbdz {
  fill: currentColor;
  d: path("M25.5 29a.5.5 0 0 1 0 1h-20a.5.5 0 0 1 0-1zM15.147 2.147a.5.5 0 0 1 .707 0l8 8a.5.5 0 1 1-.707.707L16 3.707V25.5a.5.5 0 0 1-1 0V3.707l-7.146 7.147a.5.5 0 0 1-.708-.707z");
}

</style>
