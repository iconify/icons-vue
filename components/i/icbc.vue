<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y5voevofe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:icbc" /></template>
<style>
.y5voevofe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.27 42.5H5.5V28.44h12.46v-8.88H5.5V5.5h15.77m5.46 0H42.5v14.06H30.04v8.88H42.5V42.5H26.73");
}

</style>
