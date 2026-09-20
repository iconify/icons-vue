<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="khj3mt9_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-warning-16-regular" /></template>
<style>
.khj3mt9_m {
  fill: currentColor;
  d: path("M3.603 7.554a1 1 0 0 1 1.79-.001l3.5 6.999A1 1 0 0 1 7.998 16H1.003a1 1 0 0 1-.896-1.448zm.895 6.445a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1M9 0a7 7 0 0 1 .72 13.963l-.485-.97A5.998 5.998 0 0 0 9 1a6 6 0 0 0-5.99 5.665a2 2 0 0 0-.298.442L2.12 8.29A7 7 0 0 1 9 0M4.498 8.995a.5.5 0 0 0-.5.5v3.002a.5.5 0 1 0 1 0V9.495a.5.5 0 0 0-.5-.5M8.5 3a.5.5 0 0 1 .5.5V7h2.5a.5.5 0 1 1 0 1h-3a.5.5 0 0 1-.5-.5v-4a.5.5 0 0 1 .5-.5");
}

</style>
