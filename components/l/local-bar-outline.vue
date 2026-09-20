<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukljmn1xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:local-bar-outline" /></template>
<style>
.ukljmn1xh {
  fill: currentColor;
  d: path("M7 20.5v-1h4.5v-6.462L4.346 5V4h15.308v1L12.5 13.038V19.5H17v1zM7.45 7h9.1l1.8-2H5.65zM12 12.1L15.66 8H8.34zm0 0");
}

</style>
