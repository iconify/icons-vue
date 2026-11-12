<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zagazobpz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-line-multi-fill-sharp" /></template>
<style>
.zagazobpz {
  fill: currentColor;
  d: path("M10.293 5.293A1 1 0 0 1 11.6 5.2l3.306 2.48l5.387-5.387a.999.999 0 1 1 1.414 1.414l-6 6A1 1 0 0 1 14.4 9.8l-3.306-2.48l-3.387 3.387a.999.999 0 1 1-1.414-1.414ZM4 19h17a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1V4a1 1 0 0 1 2 0Zm2.4-3.8l4-3a1 1 0 0 1 1.047-.094l3.415 1.707l5.498-4.581a1 1 0 1 1 1.28 1.536l-6 5a1 1 0 0 1-1.087.126l-3.447-1.723L7.6 16.8a1.002 1.002 0 0 1-1.593-.68a1 1 0 0 1 .393-.92");
}

</style>
