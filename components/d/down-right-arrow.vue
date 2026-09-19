<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ie88ptbik"/><path class="n6v36r40t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:down-right-arrow" /></template>
<style>
.ie88ptbik {
  fill: var(--svg-color--1b75bb, #1b75bb);
  d: path("M64 57.1a6.9 6.9 0 0 1-6.898 6.903H6.892A6.9 6.9 0 0 1-.004 57.1V6.9A6.9 6.9 0 0 1 6.892.001h50.21A6.9 6.9 0 0 1 64 6.9z");
}

.n6v36r40t {
  fill: var(--svg-color--fff, #fff);
  d: path("m47.972 23.11l2.205 24.353l-24.339-1.267c-1.715-1.932-1.975-4.567-.521-6.082l2.467-2.569l-12.07-11.578a5.103 5.103 0 0 1-.152-7.208l4.58-4.768a5.1 5.1 0 0 1 7.208-.15L39.41 25.42l2.463-2.573c1.453-1.511 4.093-1.365 6.094.263");
}

</style>
