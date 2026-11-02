<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="podydqlid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-fill-sharp" /></template>
<style>
.podydqlid {
  fill: currentColor;
  d: path("M2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v13.586l-4.293-4.293a1 1 0 0 0-1.414 0L14 14.586l-4.293-4.293a1 1 0 0 0-1.414 0ZM13 8a2 2 0 1 0 3.999.001A2 2 0 0 0 13 8m8.707 11.121a1 1 0 0 0 .293.203V21a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-1.676a1 1 0 0 0 .293-.203L9 12.414l4.293 4.293a1 1 0 0 0 1.414 0L17 14.414Z");
}

</style>
