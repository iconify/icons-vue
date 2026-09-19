<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aok6bmb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-calendar-view-day" /></template>
<style>
.aok6bmb8m {
  fill: currentColor;
  d: path("M3 17h18v2H3zm0-7h18v5H3zm0-4h18v2H3z");
}

</style>
