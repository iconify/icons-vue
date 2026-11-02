<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkqathb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-right-down-bulk-round" /></template>
<style>
.nkqathb3u {
  fill: currentColor;
  d: path("m14.293 21.707l-4-4a.999.999 0 1 1 1.414-1.414L14 18.586V7a3 3 0 0 0-3-3H9a3 3 0 0 0-3 3v6a1 1 0 0 1-2 0V7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v11.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
