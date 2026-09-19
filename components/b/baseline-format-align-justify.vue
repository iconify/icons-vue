<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkmz62b4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-format-align-justify" /></template>
<style>
.vkmz62b4k {
  fill: currentColor;
  d: path("M3 21h18v-2H3zm0-4h18v-2H3zm0-4h18v-2H3zm0-4h18V7H3zm0-6v2h18V3z");
}

</style>
