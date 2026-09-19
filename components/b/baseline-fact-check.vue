<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dcd2jgbug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-fact-check" /></template>
<style>
.dcd2jgbug {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 3H4c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2M10 17H5v-2h5zm0-4H5v-2h5zm0-4H5V7h5zm4.82 6L12 12.16l1.41-1.41l1.41 1.42L17.99 9l1.42 1.42z");
}

</style>
