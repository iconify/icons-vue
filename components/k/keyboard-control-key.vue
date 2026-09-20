<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpwtlxjjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-control-key" /></template>
<style>
.fpwtlxjjl {
  fill: currentColor;
  d: path("M6.4 12.689L5.712 12L12 5.712L18.288 12l-.688.689L12 7.114z");
}

</style>
