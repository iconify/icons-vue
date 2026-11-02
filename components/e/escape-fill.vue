<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bx39qjexu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:escape-fill" /></template>
<style>
.bx39qjexu {
  fill: currentColor;
  d: path("M12 3a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9a1 1 0 0 1 2 0a6.9 6.9 0 0 0 .55 2.724a7.002 7.002 0 0 0 12.9 0a6.99 6.99 0 0 0-1.5-7.674A6.97 6.97 0 0 0 12 5a1 1 0 0 1 0-2m-.707 9.707L5 6.414V8a1 1 0 0 1-2 0V4a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2H6.414l6.293 6.293a.999.999 0 1 1-1.414 1.414");
}

</style>
