<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kuuqcpdqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cotton-candy-stick" /></template>
<style>
.kuuqcpdqg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.343 16.086q-1.746.482-3.298-.887q-1.813-1.6-1.151-3.779q-1.123-1.384-.667-3.207q.435-1.739 1.948-2.45Q4.934 2.96 7.787 1.89Q10.389.914 12 2.717q1.611-1.803 4.213-.827q2.853 1.07 2.612 3.873q1.513.711 1.948 2.45q.456 1.823-.667 3.207q.662 2.179-1.151 3.779q-1.552 1.369-3.298.887q-.434 2.33-2.907 2.622V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-2.792q-2.473-.292-2.907-2.622");
}

</style>
