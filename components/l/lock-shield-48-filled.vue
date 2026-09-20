<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bszmpqcxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-48-filled" /></template>
<style>
.bszmpqcxj {
  fill: currentColor;
  d: path("M35.5 24.165a.84.84 0 0 1 1 0q1.133.84 2.277 1.455q1.38.74 2.779 1.152q1.787.529 3.611.528c.46 0 .833.37.833.825V33.9c0 5.501-3.286 9.543-9.694 12.042a.84.84 0 0 1-.612 0C32.79 44.81 30.525 43.36 28.92 41.6a11.1 11.1 0 0 1-1.86-2.75Q26.002 36.614 26 33.9v-5.775a.83.83 0 0 1 .833-.825c2.96 0 5.843-1.038 8.667-3.135M24 4a9 9 0 0 1 9 9v5.006a6.25 6.25 0 0 1 5.941 5.4a18 18 0 0 1-1.249-.846a2.84 2.84 0 0 0-3.384 0c-2.544 1.888-5.019 2.74-7.475 2.74A2.83 2.83 0 0 0 24 28.125v.375a2.5 2.5 0 0 0 0 5v.4c0 3.355 1.177 6.568 3.442 9.048q.501.547 1.065 1.052H15.25A6.25 6.25 0 0 1 9 37.75v-13.5a6.25 6.25 0 0 1 6-6.244V13a9 9 0 0 1 9-9m0 2.5a6.5 6.5 0 0 0-6.5 6.5v5h13v-5A6.5 6.5 0 0 0 24 6.5");
}

</style>
