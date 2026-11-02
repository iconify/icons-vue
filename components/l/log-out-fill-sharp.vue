<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj5rcmbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:log-out-fill-sharp" /></template>
<style>
.jj5rcmbhe {
  fill: currentColor;
  d: path("M15 17v4a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4H4v16h9v-3a1 1 0 0 1 2 0m2.293-7.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 .009 1.405l-.008.008l-.001.001l-3 3a1 1 0 0 1-1.414-1.414L18.586 13H11a1 1 0 0 1 0-2h7.586Z");
}

</style>
