<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ye0t2rd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-down-left-large-fill" /></template>
<style>
.v3ye0t2rd {
  fill: currentColor;
  d: path("M5 18v-8a1 1 0 0 1 2 0v5.586L17.293 5.293a.999.999 0 1 1 1.414 1.414L8.414 17H14a1 1 0 0 1 0 2H6a.997.997 0 0 1-1-1");
}

</style>
