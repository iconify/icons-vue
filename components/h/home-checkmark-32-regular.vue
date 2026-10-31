<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ja-30ac_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-checkmark-32-regular" /></template>
<style>
.ja-30ac_y {
  fill: currentColor;
  d: path("M13.896 2.775a3.25 3.25 0 0 1 4.209 0l9.75 8.289A3.25 3.25 0 0 1 29 13.539V26.5a2.5 2.5 0 0 1-2.5 2.5h-21A2.5 2.5 0 0 1 3 26.5V13.54c0-.953.42-1.858 1.146-2.476zM16.81 4.3a1.25 1.25 0 0 0-1.62 0l-9.75 8.287a1.25 1.25 0 0 0-.44.952V26.5a.5.5 0 0 0 .5.5h21a.5.5 0 0 0 .5-.5V13.54a1.25 1.25 0 0 0-.44-.952zm3.233 9.493a1 1 0 1 1 1.414 1.414l-6.5 6.5a1 1 0 0 1-1.414 0l-3-3a1 1 0 1 1 1.414-1.414l2.293 2.293z");
}

</style>
