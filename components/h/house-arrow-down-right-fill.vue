<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhh7oxbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-arrow-down-right-fill" /></template>
<style>
.bhh7oxbjq {
  fill: currentColor;
  d: path("M18 22H6a3 3 0 0 1-3-3v-8.092c0-.866.373-1.689 1.024-2.258l6-5.25a3 3 0 0 1 3.952 0l6 5.25A3 3 0 0 1 21 10.908V19a3 3 0 0 1-3 3M8.293 11.707L12.586 16H11a1 1 0 0 0 0 2h4a.997.997 0 0 0 1-1v-4a1 1 0 0 0-2 0v1.586l-4.293-4.293a.999.999 0 1 0-1.414 1.414");
}

</style>
