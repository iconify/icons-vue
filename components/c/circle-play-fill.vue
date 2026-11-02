<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3tbg_bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-play-fill" /></template>
<style>
.q3tbg_bmj {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M9 9v6c0 .239.075.47.216.664c.257.353.685.508 1.112.508c.39 0 .771-.104 1.119-.278l4-2a2.116 2.116 0 0 0 0-3.788l-4-2a2.5 2.5 0 0 0-1.119-.278c-.427 0-.855.155-1.112.508A1.13 1.13 0 0 0 9 9");
}

</style>
