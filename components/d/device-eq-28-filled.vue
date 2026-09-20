<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="r1ek65b0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-eq-28-filled" /></template>
<style>
.r1ek65b0j {
  fill: currentColor;
  d: path("M14 2a1 1 0 0 1 1 1v22a1 1 0 1 1-2 0V3a1 1 0 0 1 1-1M9 6a1 1 0 0 1 1 1v14a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1m10 0a1 1 0 0 1 1 1v14a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1M4 10a1 1 0 0 1 1 1v6a1 1 0 1 1-2 0v-6a1 1 0 0 1 1-1m20 0a1 1 0 0 1 1 1v6a1 1 0 1 1-2 0v-6a1 1 0 0 1 1-1");
}

</style>
