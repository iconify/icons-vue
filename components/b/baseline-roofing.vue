<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx66-bjff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-roofing" /></template>
<style>
.qx66-bjff {
  fill: currentColor;
  d: path("M13 18h-2v-2h2zm2-4H9v6h6zm4-4.7V4h-3v2.6L12 3L2 12h3l7-6.31L19 12h3z");
}

</style>
