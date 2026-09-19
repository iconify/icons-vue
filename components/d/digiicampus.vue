<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qcb72hb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digiicampus" /></template>
<style>
.qcb72hb_s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 7.5v33a2 2 0 0 0 2 2h16.057c10.031 0 18.575-7.8 18.931-17.825C42.862 14.15 34.441 5.5 24 5.5H7.5a2 2 0 0 0-2 2");
}

</style>
