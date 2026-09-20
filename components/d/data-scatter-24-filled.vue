<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzhdcsbii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-scatter-24-filled" /></template>
<style>
.mzhdcsbii {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1 1v13.5A1.5 1.5 0 0 0 6.5 19H20a1 1 0 1 1 0 2H6.5A3.5 3.5 0 0 1 3 17.5V4a1 1 0 0 1 1-1m13 1a3 3 0 1 0 0 6a3 3 0 0 0 0-6M6 9a3 3 0 1 1 6 0a3 3 0 0 1-6 0m6 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
