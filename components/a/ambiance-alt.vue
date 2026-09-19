<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i2bcp-b2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ambiance-alt" /></template>
<style>
.i2bcp-b2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.245 17.631V30.52m5.585 4.891V12.66m5.585 2.66v17.547M24 37.743V10.156M29.585 5.5v37m5.585-7.202V12.9m5.585 7.152v8.09");
}

</style>
