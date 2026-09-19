<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="knf8uec4m"/><path class="c_yummbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audeze-hq" /></template>
<style>
.c_yummbzp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.999 22.298l10.747 18.614l5.816-.003l-13.654-23.651l-4.852 8.402M4.5 35.827l2.938 5.082l5.816-.003l2.938-5.081l-2.938-5.082");
}

.knf8uec4m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.192 35.824h15.616M26.907 7.089l-5.816.002L4.5 35.828l5.816-.003l2.938-5.082h15.62l-2.934-5.081h-9.748zL43.5 35.829l-2.938 5.08");
}

</style>
