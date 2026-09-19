<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h7p24cbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:boolder" /></template>
<style>
.h7p24cbkz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.68 4.5l-8.962 5.799L9.227 43.5h25.24l4.306-13.393l-5.474-6.541l5.107-11.43z");
}

</style>
