<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="llmxtqnpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-mouse-off-20-filled" /></template>
<style>
.llmxtqnpx {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707L14.293 15H3.5A1.5 1.5 0 0 1 2 13.5v-8a1.5 1.5 0 0 1 1.307-1.486l-1.16-1.16a.5.5 0 0 1 0-.708M5.5 12a.5.5 0 0 0 0 1h6.793l-1-1zM12 7a4 4 0 0 0 6 3.463V13.5c0 .644-.406 1.19-.976 1.403l-2.116-2.116A.5.5 0 0 0 14.5 12h-.379l-8-8H12zm5.395-5C18.28 2 19 2.719 19 3.605V7a3 3 0 1 1-6 0V3.605C13 2.72 13.719 2 14.605 2zm-2.79 1a.606.606 0 0 0-.605.605V7a2 2 0 1 0 4 0V3.605A.606.606 0 0 0 17.395 3H16.5v2.5a.5.5 0 0 1-1 0V3z");
}

</style>
