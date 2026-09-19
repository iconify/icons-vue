<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebm73zbyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-send-to-mobile" /></template>
<style>
.ebm73zbyz {
  fill: currentColor;
  d: path("M17 17h2v4c0 1.1-.9 2-2 2H7c-1.1 0-2-.9-2-2V3c0-1.1.9-1.99 2-1.99L17 1c1.1 0 2 .9 2 2v4h-2V6H7v12h10zm5-5l-4-4v3h-5v2h5v3z");
}

</style>
