<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gpul7pvkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:letter-m" /></template>
<style>
.gpul7pvkh {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m14.035 44.508h-5.65V26.882q.001-.846.02-2.372q.02-1.527.02-2.353l-5.498 24.351h-5.893l-5.459-24.351q0 .826.02 2.353q.02 1.526.02 2.372v19.626h-5.65V17.492h8.824l5.281 22.814l5.242-22.814h8.725v29.016z");
}

</style>
