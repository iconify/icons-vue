<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0kjlvfhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-park" /></template>
<style>
.x0kjlvfhm {
  fill: currentColor;
  d: path("M17 12h2L12 2L5.05 12H7l-3.9 6h6.92v4h3.96v-4H21z");
}

</style>
