<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r6k4a0bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:crop-32-regular" /></template>
<style>
.r6k4a0bfl {
  fill: currentColor;
  d: path("M9 3a1 1 0 0 0-2 0v4H3a1 1 0 0 0 0 2h4v11.5a4.5 4.5 0 0 0 4.5 4.5H23v4a1 1 0 1 0 2 0v-4h4a1 1 0 1 0 0-2H11.5A2.5 2.5 0 0 1 9 20.5zm14 8.5v10h2v-10A4.5 4.5 0 0 0 20.5 7h-10v2h10a2.5 2.5 0 0 1 2.5 2.5");
}

</style>
