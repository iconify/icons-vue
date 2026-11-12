<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwvgkobau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:air-vent-fill" /></template>
<style>
.wwvgkobau {
  fill: currentColor;
  d: path("M5 2h6a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m2 15V7a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0m4 0V7a1 1 0 0 0-2 0v10a1 1 0 0 0 2 0M21 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 5a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
