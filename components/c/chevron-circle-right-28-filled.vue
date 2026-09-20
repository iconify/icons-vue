<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="vvyw_dluq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-28-filled" /></template>
<style>
.vvyw_dluq {
  fill: currentColor;
  d: path("M14 26C7.373 26 2 20.627 2 14S7.373 2 14 2s12 5.373 12 12s-5.373 12-12 12m-2.78-7.03a.75.75 0 1 0 1.06 1.06l5.5-5.5a.75.75 0 0 0 0-1.06l-5.5-5.5a.75.75 0 1 0-1.06 1.06L16.19 14z");
}

</style>
