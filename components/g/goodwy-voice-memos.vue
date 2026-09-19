<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxsveupax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goodwy-voice-memos" /></template>
<style>
.yxsveupax {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.524 21.912l.022 5.623m4.012-11.603l-.121 17.091m4.622-23.948l-.028 30.673m4.556-23.561l-.034 16.863m4.336-12.793l.058 8.805m4.012-12.982l-.112 16.865m4.815-12.651l-.051 7.921m4.508-11.889l-.02 16.332m4.489-12.19l-.027 8.218m3.914-6.437l.05 4.396");
}

</style>
