<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mfcxjca9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:avant" /></template>
<style>
.mfcxjca9j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.898 39.499l-5.966-10.333L29.966 39.5H6.102L24 8.5l5.966 10.333l-7.954 13.778");
}

</style>
