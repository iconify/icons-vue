<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh8trchkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-surprised-fill-round" /></template>
<style>
.sh8trchkr {
  fill: currentColor;
  d: path("M2.786 8.107C4.936 3.02 10.804.639 15.892 2.788s7.469 8.016 5.32 13.104s-8.016 7.469-13.104 5.32S.637 13.195 2.786 8.107M9 8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm6 0a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm-6 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
