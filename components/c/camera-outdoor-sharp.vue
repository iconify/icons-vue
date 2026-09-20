<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzdnx98du"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:camera-outdoor-sharp" /></template>
<style>
.qzdnx98du {
  fill: currentColor;
  d: path("M5 20V9.5l7-5.27l7 5.27V11h-8.461v8H19v1zm6.923-2.384v-5.231h5.23v2.077L19 13.489v3.022l-1.846-.972v2.077z");
}

</style>
