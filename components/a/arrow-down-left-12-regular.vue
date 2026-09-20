<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="e3tzezzku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-left-12-regular" /></template>
<style>
.e3tzezzku {
  fill: currentColor;
  d: path("M10.854 1.146a.5.5 0 0 1 0 .708L2.707 10H7.53a.5.5 0 0 1 0 1H1.5a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 1 0v4.793l8.146-8.147a.5.5 0 0 1 .708 0");
}

</style>
