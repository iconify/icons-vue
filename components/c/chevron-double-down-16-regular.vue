<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i65yfwb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-double-down-16-regular" /></template>
<style>
.i65yfwb6u {
  fill: currentColor;
  d: path("M3.146 7.646a.5.5 0 0 1 .707 0L8 11.793l4.147-4.147a.501.501 0 0 1 .707.707l-4.5 4.5a.5.5 0 0 1-.707 0l-4.5-4.5a.5.5 0 0 1 0-.707m0-4a.5.5 0 0 1 .707 0L8 7.793l4.147-4.147a.501.501 0 0 1 .707.707l-4.5 4.5a.5.5 0 0 1-.707 0l-4.5-4.5a.5.5 0 0 1 0-.707");
}

</style>
