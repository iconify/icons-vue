<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="tsujvvbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:hourglass-high-bold" /></template>
<style>
.tsujvvbyb {
  fill: currentColor;
  d: path("M184 20H72a20 20 0 0 0-20 20v36a20.1 20.1 0 0 0 8 16l48 36l-48 36a20.1 20.1 0 0 0-8 16v36a20 20 0 0 0 20 20h112a20 20 0 0 0 20-20v-35.64a20.13 20.13 0 0 0-7.94-16L147.9 128l48.16-36.4a20.13 20.13 0 0 0 7.94-16V40a20 20 0 0 0-20-20m-4 24v16H76V44Zm-52 69L89.33 84h77Zm52 99H76v-30l52-39l52 39.33Z");
}

</style>
