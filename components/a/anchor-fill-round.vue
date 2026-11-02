<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxurvwbnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:anchor-fill-round" /></template>
<style>
.kxurvwbnr {
  fill: currentColor;
  d: path("M13 7.829V10h2a1 1 0 0 1 0 2h-2v7.939A8.015 8.015 0 0 0 19.939 13H19a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1c0 5.523-4.477 10-10 10S2 17.523 2 12a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2h-.939A8.015 8.015 0 0 0 11 19.939V12H9a1 1 0 0 1 0-2h2V7.829a3 3 0 1 1 2 0m-.293-2.122a.999.999 0 1 0-1.414-1.414a.999.999 0 1 0 1.414 1.414");
}

</style>
