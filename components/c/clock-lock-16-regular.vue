<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vrnhu8x7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clock-lock-16-regular" /></template>
<style>
.vrnhu8x7m {
  fill: currentColor;
  d: path("M8 15v-1a6 6 0 1 0-5.748-7.73a3 3 0 0 0-1.217 1.02A7 7 0 1 1 8 15M8 4.5a.5.5 0 1 0-1 0v4a.5.5 0 0 0 .5.5h3a.5.5 0 0 0 0-1H8zM1.5 9v1H1a1 1 0 0 0-1 1v4a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-4a1 1 0 0 0-1-1h-.5V9a2 2 0 1 0-4 0m1 1V9a1 1 0 0 1 2 0v1zm1 2.25a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
