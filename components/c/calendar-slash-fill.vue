<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wpfgwhvvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:calendar-slash-fill" /></template>
<style>
.wpfgwhvvq {
  fill: currentColor;
  d: path("M224 48v139.57a4 4 0 0 1-7 2.7L116.8 80H208V48h-24v8a8 8 0 0 1-8.52 8a8.18 8.18 0 0 1-7.48-8.27V48H87.71l-8.46-9.31a4 4 0 0 1 3-6.69H168v-8a8 8 0 0 1 8.52-8a8.18 8.18 0 0 1 7.48 8.27V32h24a16 16 0 0 1 16 16m-10.08 162.62A8 8 0 0 1 208 224H48a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16a8 8 0 0 1 5.93 2.62ZM73.55 80L48 51.89V80Z");
}

</style>
