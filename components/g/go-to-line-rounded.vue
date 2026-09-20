<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgs1zsodr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:go-to-line-rounded" /></template>
<style>
.zgs1zsodr {
  fill: currentColor;
  d: path("M11.293 6.709Q11 6.418 11 6.002t.291-.709t.707-.293t.709.291t.293.707t-.291.709t-.707.293t-.709-.291m0 12Q11 18.418 11 18.002t.291-.709t.707-.293t.709.291t.293.707t-.291.709t-.707.293t-.709-.291");
}

</style>
