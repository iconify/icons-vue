<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w9q-ex8dx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-32-filled" /></template>
<style>
.w9q-ex8dx {
  fill: currentColor;
  d: path("M10.2 3A4.2 4.2 0 0 0 6 7.2V28a1 1 0 0 0 1.585.81L16 22.735l8.415 6.077A1 1 0 0 0 26 28V7.2A4.2 4.2 0 0 0 21.8 3z");
}

</style>
