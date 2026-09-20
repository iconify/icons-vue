<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x2e6o3b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:device-mobile-slash-fill" /></template>
<style>
.x2e6o3b-p {
  fill: currentColor;
  d: path("M213.38 221.92a8 8 0 0 1-11.3-.54l-2.26-2.48A24 24 0 0 1 176 240H80a24 24 0 0 1-24-24V60.69L42.08 45.38a8 8 0 1 1 11.84-10.76l160 176a8 8 0 0 1-.54 11.3m-27.3-65.71a8 8 0 0 0 13.92-5.38V40a24 24 0 0 0-24-24H76.7a8 8 0 0 0-5.92 13.38Z");
}

</style>
