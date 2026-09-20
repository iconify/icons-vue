<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u52u4h80x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-2-3-outline-sharp" /></template>
<style>
.u52u4h80x {
  fill: currentColor;
  d: path("M6 22V2h12v20zm2-2h8V4H8zm0 0V4z");
}

</style>
