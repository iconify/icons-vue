<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hyjte739d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dark-theme-20-regular" /></template>
<style>
.hyjte739d {
  fill: currentColor;
  d: path("M10 3a7 7 0 1 1 0 14zm0-1a8 8 0 1 0 0 16a8 8 0 0 0 0-16");
}

</style>
