<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m4yo7fmsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-holiday-village" /></template>
<style>
.m4yo7fmsq {
  fill: currentColor;
  d: path("M18 20V8.35L13.65 4h-2.83L16 9.18V20zm4 0V6.69L19.31 4h-2.83L20 7.52V20zM8 4l-6 6v10h5v-5h2v5h5V10zm1 9H7v-2h2z");
}

</style>
