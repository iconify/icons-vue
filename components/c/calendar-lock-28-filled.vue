<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="q4-9dzblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-lock-28-filled" /></template>
<style>
.q4-9dzblg {
  fill: currentColor;
  d: path("M25 9.5v5.562A4 4 0 0 0 17.5 17v.041A3 3 0 0 0 15 20v5H6.25A3.25 3.25 0 0 1 3 21.75V9.5zM21.75 3A3.25 3.25 0 0 1 25 6.25V8H3V6.25A3.25 3.25 0 0 1 6.25 3zM18.5 18H18a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h7a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2h-.5v-1a3 3 0 1 0-6 0zm1.5-1a1.5 1.5 0 0 1 3 0v1h-3zm3 5.5a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

</style>
