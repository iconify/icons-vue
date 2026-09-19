<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qr_gxr03b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:comdirect" /></template>
<style>
.qr_gxr03b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.53 3.552a20.32 20.32 0 0 0-12.955 5.952a20.585 20.585 0 0 0 0 28.991a20.29 20.29 0 0 0 28.819 0l-6.551-6.59a11.07 11.07 0 0 1-15.717 0a11.23 11.23 0 0 1 0-15.81a11.07 11.07 0 0 1 15.717 0l6.55-6.59A20.3 20.3 0 0 0 25.53 3.552");
}

</style>
