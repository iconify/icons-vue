<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f41futk8u"/><path class="hwr0mfb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:krungthai-npa" /></template>
<style>
.f41futk8u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.36 40.91v-8.787h2.876a2.95 2.95 0 0 1 2.945 2.951a2.95 2.95 0 0 1-2.945 2.951H22.36M34.579 38h-3.893");
}

.hwr0mfb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.722 40.91l2.91-8.787l2.911 8.787h6.154V22.644L24 7.09L6.303 22.644V40.91h6.345v-8.787l5.822 8.787v-8.787");
}

</style>
