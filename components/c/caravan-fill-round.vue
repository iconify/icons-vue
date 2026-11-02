<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ato9klb9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caravan-fill-round" /></template>
<style>
.ato9klb9g {
  fill: currentColor;
  d: path("M7 4h6a5 5 0 0 1 5 5v5h3a1 1 0 0 1 0 2h-3a3 3 0 0 1-3 3h-2.171a3 3 0 0 1-5.658 0H5a3 3 0 0 1-3-3V9a5 5 0 0 1 5-5m-1 6v2a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-2a2 2 0 0 0-2-2H8a2 2 0 0 0-2 2m3.293 8.707l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

</style>
