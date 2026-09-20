<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="e4-yj0lqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:command-fill" /></template>
<style>
.e4-yj0lqd {
  fill: currentColor;
  d: path("M116 116h24v24h-24ZM86 72a14 14 0 0 0 0 28h14V86a14 14 0 0 0-14-14m98 14a14 14 0 0 0-28 0v14h14a14 14 0 0 0 14-14M72 170a14 14 0 0 0 28 0v-14H86a14 14 0 0 0-14 14M224 48v160a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16m-68 92v-24h14a30 30 0 1 0-30-30v14h-24V86a30 30 0 1 0-30 30h14v24H86a30 30 0 1 0 30 30v-14h24v14a30 30 0 1 0 30-30Zm0 30a14 14 0 1 0 14-14h-14Z");
}

</style>
