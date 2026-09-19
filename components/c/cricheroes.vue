<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p3g4y0bgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cricheroes" /></template>
<style>
.p3g4y0bgy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 34.008l2.076-2.594s3.659-.649 8.986-4.355c-1.204 6.856-8.57 8.292-8.57 8.292c-.025 2.909-.616 5.97-1.148 8.149h0c8.228-1.185 14.693-13.038 14.693-22.963C40.037 11.68 32.857 4.5 24 4.5S7.963 11.68 7.963 20.537c0 9.925 6.465 21.778 14.693 22.963h0c-.532-2.18-1.123-5.24-1.148-8.149c0 0-7.366-1.436-8.57-8.292c5.327 3.706 8.987 4.355 8.987 4.355z");
}

</style>
