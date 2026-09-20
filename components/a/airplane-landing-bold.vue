<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xmb_g2mqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:airplane-landing-bold" /></template>
<style>
.xmb_g2mqe {
  fill: currentColor;
  d: path("M256 216a12 12 0 0 1-12 12H104a12 12 0 0 1 0-24h140a12 12 0 0 1 12 12m-27.24-24.45L52.14 142.09A44.13 44.13 0 0 1 20 99.72V48a20 20 0 0 1 26.32-19l5.48 1.83a12 12 0 0 1 7.49 7.3l9.91 27.46l22.8 6.5V48a20 20 0 0 1 26.32-19l5.48 1.83a12 12 0 0 1 7.27 6.74l21.75 51.85l59 16.49A44.12 44.12 0 0 1 244 148.32V180a12 12 0 0 1-15.24 11.55M220 148.32a20.05 20.05 0 0 0-14.65-19.27L140.77 111a12 12 0 0 1-7.84-6.91L116 63.71V88a12 12 0 0 1-15.29 11.54L56.71 87a12 12 0 0 1-8-7.46L44 66.48v33.24A20.07 20.07 0 0 0 58.61 119L220 164.18Z");
}

</style>
