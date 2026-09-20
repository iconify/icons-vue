<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6hp51yfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-shift-24-filled" /></template>
<style>
.e6hp51yfu {
  fill: currentColor;
  d: path("M10.677 2.603a1.75 1.75 0 0 1 2.644 0l8.246 9.504c.983 1.133.178 2.897-1.322 2.897H17v5.247A1.75 1.75 0 0 1 15.25 22h-6.5A1.75 1.75 0 0 1 7 20.25v-5.247H3.754c-1.5 0-2.305-1.764-1.322-2.897z");
}

</style>
