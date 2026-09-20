<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t818sf2kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-multiple-concentric-24-filled" /></template>
<style>
.t818sf2kr {
  fill: currentColor;
  d: path("M4 12a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8-10C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2M8 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-6a6 6 0 1 0 0 12a6 6 0 0 0 0-12");
}

</style>
