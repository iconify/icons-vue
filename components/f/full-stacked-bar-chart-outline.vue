<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdy_qvbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:full-stacked-bar-chart-outline" /></template>
<style>
.sdy_qvbwk {
  fill: currentColor;
  d: path("M5 19v-2.808h3V19zm0-3.577v-3h3v3zm0-3.77V5h3v6.654zM10.52 19v-6.654h3V19zm0-7.423v-3h3v3zm0-3.77V5h3v2.808zM16 19v-1.884h3V19zm0-2.654v-3h3v3zm0-3.769V5h3v7.577z");
}

</style>
