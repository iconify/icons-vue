<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="nnmpa2y7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bounce-28-regular" /></template>
<style>
.nnmpa2y7g {
  fill: currentColor;
  d: path("M2 7.75A.75.75 0 0 1 2.75 7h8.5a.75.75 0 0 1 0 1.5H4.615l10.387 9.963l9.731-9.256a.75.75 0 1 1 1.034 1.086l-10.25 9.75a.75.75 0 0 1-1.036-.002L3.5 9.51v6.741a.75.75 0 0 1-1.5 0z");
}

</style>
