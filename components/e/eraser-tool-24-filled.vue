<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmg_gs_tp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:eraser-tool-24-filled" /></template>
<style>
.wmg_gs_tp {
  fill: currentColor;
  d: path("M4.5 2.75a.75.75 0 0 0-1.5 0v14.5A4.75 4.75 0 0 0 7.75 22h8.5A4.75 4.75 0 0 0 21 17.25V2.75a.75.75 0 0 0-1.5 0V7h-15zm0 5.75h15V12h-15z");
}

</style>
