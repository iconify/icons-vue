<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdyz72o0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-column-left-outline" /></template>
<style>
.wdyz72o0x {
  fill: currentColor;
  d: path("M20 19V5h-6.558v14zM5 20v-3.116h1V19h6.442V5H6v2.116H5V4h16v16zm8.442-8h-1zM5 14.5v-2H3v-1h2v-2h1v2h2v1H6v2z");
}

</style>
