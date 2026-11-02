<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvrzffbme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-close-fill-round" /></template>
<style>
.dvrzffbme {
  fill: currentColor;
  d: path("m17.707 18.707l-2 2a5.243 5.243 0 0 1-7.414 0l-5-5a5.243 5.243 0 0 1 0-7.414l5-5a5.243 5.243 0 0 1 7.414 0l5 5a5.243 5.243 0 0 1 0 7.414Zm-7-9.414a.999.999 0 1 0-1.414 1.414L10.586 12l-1.293 1.293a.999.999 0 1 0 1.414 1.414L12 13.414l1.293 1.293a.999.999 0 1 0 1.414-1.414L13.414 12l1.293-1.293a.999.999 0 1 0-1.414-1.414L12 10.586Z");
}

</style>
