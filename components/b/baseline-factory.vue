<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8tcqbwjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-factory" /></template>
<style>
.g8tcqbwjl {
  fill: currentColor;
  d: path("M22 10v12H2V10l7-3v2l5-2v3zm-4.8-1.5L18 2h3l.8 6.5zM11 18h2v-4h-2zm-4 0h2v-4H7zm10-4h-2v4h2z");
}

</style>
