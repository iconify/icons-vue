<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_20igflh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-festival" /></template>
<style>
.d_20igflh {
  fill: currentColor;
  d: path("M13 5.7V4h3l-1-1.49L16 1h-5v4.7L2 12v10h7v-5l3.03-2L15 17v5h7V12z");
}

</style>
