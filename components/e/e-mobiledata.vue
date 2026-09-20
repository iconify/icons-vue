<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qo8v-yb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:e-mobiledata" /></template>
<style>
.qo8v-yb4b {
  fill: currentColor;
  d: path("M8 17V7h8v2h-6v2h6v2h-6v2h6v2z");
}

</style>
