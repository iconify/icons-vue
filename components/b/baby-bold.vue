<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wzb-3m-rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:baby-bold" /></template>
<style>
.wzb-3m-rs {
  fill: currentColor;
  d: path("M92 144a16 16 0 1 1 16-16a16 16 0 0 1-16 16m72-32a16 16 0 1 0 16 16a16 16 0 0 0-16-16m-14.4 49.85a41 41 0 0 1-43.2 0a12 12 0 1 0-12.8 20.3a65 65 0 0 0 68.8 0a12 12 0 1 0-12.8-20.3M236 128A108 108 0 1 1 128 20a108.12 108.12 0 0 1 108 108m-24 0a84.08 84.08 0 0 0-82-83.95c-9.46 14.2-10 27.28-10 28a8 8 0 0 0 16-.05a12 12 0 0 1 24 0a32 32 0 0 1-64 0c0-.63.1-10.48 5-23.52A84 84 0 1 0 212 128");
}

</style>
