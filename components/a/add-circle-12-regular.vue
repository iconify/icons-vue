<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mp45hpx4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-circle-12-regular" /></template>
<style>
.mp45hpx4v {
  fill: currentColor;
  d: path("M6 3.5c.23 0 .417.187.417.417v1.666h1.666a.417.417 0 0 1 0 .834H6.417v1.666a.417.417 0 0 1-.834 0V6.417H3.917a.417.417 0 0 1 0-.834h1.666V3.917c0-.23.187-.417.417-.417M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m5-4.167a4.167 4.167 0 1 0 0 8.334a4.167 4.167 0 0 0 0-8.334");
}

</style>
