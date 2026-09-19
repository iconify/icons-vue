<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g4g40cbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cjp" /></template>
<style>
.g4g40cbib {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.317 19.305h13.861a2.45 2.45 0 0 1 2.449 2.448v1.483a2.45 2.45 0 0 1-2.449 2.449h-7.616v3.01m-6.245-6.2v4.044a2.157 2.157 0 0 1-2.157 2.156h-8.896m0-6.2v-1.056c0-.93-.754-1.685-1.685-1.685H6.312c-.93 0-1.685.754-1.685 1.685v5.571c0 .93.754 1.685 1.685 1.685h6.582");
}

</style>
