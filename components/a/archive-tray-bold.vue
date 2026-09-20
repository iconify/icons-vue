<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="y2fw4w6hg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:archive-tray-bold" /></template>
<style>
.y2fw4w6hg {
  fill: currentColor;
  d: path("M208 28H48a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h160a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m-4 24v96h-24.69a19.86 19.86 0 0 0-14.14 5.86L147 172h-38l-18.17-18.14A19.86 19.86 0 0 0 76.69 148H52V52ZM52 204v-32h23l18.14 18.14a19.86 19.86 0 0 0 14.17 5.86h41.38a19.86 19.86 0 0 0 14.14-5.86L181 172h23v32Zm35.51-79.51a12 12 0 0 1 17-17L116 119V76a12 12 0 0 1 24 0v43l11.51-11.52a12 12 0 0 1 17 17l-32 32a12 12 0 0 1-17 0Z");
}

</style>
