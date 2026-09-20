<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="fvmjmjgko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-28-filled" /></template>
<style>
.fvmjmjgko {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l22.5 22.5a.75.75 0 0 1-1.06 1.06l-2.784-2.784A11.95 11.95 0 0 1 14 26C7.373 26 2 20.627 2 14c0-3.044 1.134-5.822 3.002-7.937L2.22 3.28a.75.75 0 0 1 0-1.06M14 2c6.627 0 12 5.373 12 12c0 2.5-.766 4.821-2.074 6.743L7.256 4.073A11.94 11.94 0 0 1 14 2");
}

</style>
