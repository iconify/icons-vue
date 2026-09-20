<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjtor2blf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:key-command-24-filled" /></template>
<style>
.cjtor2blf {
  fill: currentColor;
  d: path("M6.5 5A1.5 1.5 0 0 1 8 6.5V8H6.5a1.5 1.5 0 1 1 0-3M10 8V6.5A3.5 3.5 0 1 0 6.5 10H8v4H6.5a3.5 3.5 0 1 0 3.5 3.5V16h4v1.5a3.5 3.5 0 1 0 3.5-3.5H16v-4h1.5A3.5 3.5 0 1 0 14 6.5V8zm0 2h4v4h-4zm6-2V6.5A1.5 1.5 0 1 1 17.5 8zm0 8h1.5a1.5 1.5 0 1 1-1.5 1.5zm-8 0v1.5A1.5 1.5 0 1 1 6.5 16z");
}

</style>
