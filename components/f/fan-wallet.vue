<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i-s9z6xyj"/><path class="jli6dobky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fan-wallet" /></template>
<style>
.i-s9z6xyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.42 27.483a1.743 1.743 0 0 1-1.7-3.044L26.415 6.002a2.92 2.92 0 0 0-3.98-1.128L8.53 12.643a2.92 2.92 0 0 0-1.127 3.983l10.303 18.437a1.743 1.743 0 0 1 1.703 3.043h-.002L21.583 42a2.92 2.92 0 0 0 3.982 1.125l13.906-7.768a2.917 2.917 0 0 0 1.126-3.98z");
}

.jli6dobky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.775 16.347l-2.326 13.19c-.216 1.224.602 2.217 1.826 2.217h.665m-3.141-11.755h4.651");
}

</style>
