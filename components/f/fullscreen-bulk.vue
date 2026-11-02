<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m6jkovbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-bulk" /></template>
<style>
.m6jkovbup {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h3a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v3a1 1 0 0 1-2 0Zm17-3a3 3 0 0 1 3 3v3a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-3a1 1 0 0 1 0-2ZM5 22a3 3 0 0 1-3-3v-3a1 1 0 0 1 2 0v3a1 1 0 0 0 1 1h3a1 1 0 0 1 0 2Zm17-3a3 3 0 0 1-3 3h-3a1 1 0 0 1 0-2h3a1 1 0 0 0 1-1v-3a1 1 0 0 1 2 0Z");
}

</style>
