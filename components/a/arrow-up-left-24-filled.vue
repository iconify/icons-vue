<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkq8tu_hy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-up-left-24-filled" /></template>
<style>
.bkq8tu_hy {
  fill: currentColor;
  d: path("M13 3a1 1 0 1 1 0 2H6.414l14.293 14.293a1 1 0 0 1-1.414 1.414L5 6.414V13a1 1 0 1 1-2 0V4a1 1 0 0 1 1-1z");
}

</style>
