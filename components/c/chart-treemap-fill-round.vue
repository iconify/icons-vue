<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqu48-7cw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-treemap-fill-round" /></template>
<style>
.lqu48-7cw {
  fill: currentColor;
  d: path("M9 2v20H7a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5Zm2 7V2h6a5 5 0 0 1 5 5v2Zm4 13h-4V11h4Zm7-11v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22V11Z");
}

</style>
