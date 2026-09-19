<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zamwb1b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-report-problem" /></template>
<style>
.zamwb1b7d {
  fill: currentColor;
  d: path("M1 21h22L12 2zm12-3h-2v-2h2zm0-4h-2v-4h2z");
}

</style>
