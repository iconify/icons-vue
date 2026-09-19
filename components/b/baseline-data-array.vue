<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slm8u7s3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-data-array" /></template>
<style>
.slm8u7s3p {
  fill: currentColor;
  d: path("M15 4v2h3v12h-3v2h5V4zM4 20h5v-2H6V6h3V4H4z");
}

</style>
