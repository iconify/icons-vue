<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qkk-07bbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sensor-outline-sharp" /></template>
<style>
.qkk-07bbh {
  fill: currentColor;
  d: path("M9 15V5v14zm-1 .5h1V19h6V5H9v9.5H8V4h8v16H8zm4-5.73q.31 0 .54-.23t.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23m7-6.27h1v5h-1zm-6.23 12H5.384v-1h7.384z");
}

</style>
