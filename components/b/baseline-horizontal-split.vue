<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8atucppv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-horizontal-split" /></template>
<style>
.h8atucppv {
  fill: currentColor;
  d: path("M3 19h18v-6H3zm0-8h18V9H3zm0-6v2h18V5z");
}

</style>
