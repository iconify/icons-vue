<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="w1rxcqb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:item-compare-28-regular" /></template>
<style>
.w1rxcqb3c {
  fill: currentColor;
  d: path("M14 3a.75.75 0 0 1 .75.75v20.5a.75.75 0 0 1-1.5 0V3.75A.75.75 0 0 1 14 3M8.25 9A2.75 2.75 0 0 1 11 11.75v4.5A2.75 2.75 0 0 1 8.25 19h-4.5A2.75 2.75 0 0 1 1 16.25v-4.5A2.75 2.75 0 0 1 3.75 9zm16 0A2.75 2.75 0 0 1 27 11.75v4.5A2.75 2.75 0 0 1 24.25 19h-4.5A2.75 2.75 0 0 1 17 16.25v-4.5A2.75 2.75 0 0 1 19.75 9zm-20.5 1.5c-.69 0-1.25.56-1.25 1.25v4.5c0 .69.56 1.25 1.25 1.25h4.5c.69 0 1.25-.56 1.25-1.25v-4.5c0-.69-.56-1.25-1.25-1.25zm16 0c-.69 0-1.25.56-1.25 1.25v4.5c0 .69.56 1.25 1.25 1.25h4.5c.69 0 1.25-.56 1.25-1.25v-4.5c0-.69-.56-1.25-1.25-1.25z");
}

</style>
