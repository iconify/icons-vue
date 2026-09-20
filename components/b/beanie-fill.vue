<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vhjfslbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:beanie-fill" /></template>
<style>
.vhjfslbwl {
  fill: currentColor;
  d: path("M224 162.16V144a96.18 96.18 0 0 0-72.34-93a28 28 0 1 0-47.32 0A96.18 96.18 0 0 0 32 144v18.16A16 16 0 0 0 24 176v32a16 16 0 0 0 16 16h176a16 16 0 0 0 16-16v-32a16 16 0 0 0-8-13.84M120 176v32H80v-32Zm16 0h40v32h-40ZM116 36a12 12 0 1 1 12 12a12 12 0 0 1-12-12M40 176h24v32H40Zm176 32h-24v-32h24z");
}

</style>
