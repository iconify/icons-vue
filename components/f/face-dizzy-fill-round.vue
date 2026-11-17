<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_eu81bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-dizzy-fill-round" /></template>
<style>
.s_eu81bii {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m7-4.414l-.293-.293a.999.999 0 1 0-1.414 1.414L7.586 9l-.293.293a.999.999 0 1 0 1.414 1.414L9 10.414l.293.293a.999.999 0 1 0 1.414-1.414L10.414 9l.293-.293a.999.999 0 1 0-1.414-1.414ZM16.414 9l.293-.293a.999.999 0 1 0-1.414-1.414L15 7.586l-.293-.293a.999.999 0 1 0-1.414 1.414l.293.293l-.293.293a.999.999 0 1 0 1.414 1.414l.293-.293l.293.293a.999.999 0 1 0 1.414-1.414Zm-7.707 4.293a.999.999 0 1 0-1.414 1.414a6.653 6.653 0 0 0 9.414 0a1.002 1.002 0 0 0-1.414-1.414a4.656 4.656 0 0 1-6.586 0");
}

</style>
