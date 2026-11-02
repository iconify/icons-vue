<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgy9mv7hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-fill-round" /></template>
<style>
.cgy9mv7hu {
  fill: currentColor;
  d: path("M5 18.829A3 3 0 0 1 3 16v-6c0-.155.036-.308.106-.447l2-4C5.848 4.069 7.307 3 9 3h6c1.693 0 3.152 1.069 3.894 2.553l2 4c.07.139.106.292.106.447v6c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-1H9v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1ZM12.414 10l1.293-1.293a.999.999 0 1 0-1.414-1.414l-3 3A1 1 0 0 0 10 12h1.586l-1.293 1.293a.999.999 0 1 0 1.414 1.414l3-3A1 1 0 0 0 14 10Z");
}

</style>
