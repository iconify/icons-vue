<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gx3qayd4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:device-mobile-camera-fill" /></template>
<style>
.gx3qayd4p {
  fill: currentColor;
  d: path("M176 16H80a24 24 0 0 0-24 24v176a24 24 0 0 0 24 24h96a24 24 0 0 0 24-24V40a24 24 0 0 0-24-24m-48 56a12 12 0 1 1 12-12a12 12 0 0 1-12 12");
}

</style>
