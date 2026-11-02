<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpsi_yblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calculator-fill-round" /></template>
<style>
.rpsi_yblc {
  fill: currentColor;
  d: path("M8 2h8a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5V7a5 5 0 0 1 5-5m0 5a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Zm.01 4H8a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2m4 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M17 16v-4a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0m-9-1a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm4.01 0H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
