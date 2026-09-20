<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vazor4bnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-arrow-back-48-filled" /></template>
<style>
.vazor4bnq {
  fill: currentColor;
  d: path("M35 24c6.075 0 11 4.925 11 11s-4.925 11-11 11s-11-4.925-11-11s4.925-11 11-11M8 17.398q.485.1 1 .102h30q.515-.001 1-.1v5.596A13 13 0 0 0 35 22c-2.173 0-4.222.534-6.023 1.477q.022-.111.023-.227c0-.69-.56-1.25-1.25-1.25h-7.5a1.25 1.25 0 1 0 0 2.5h7.085A12.98 12.98 0 0 0 22 35c0 2.577.75 4.98 2.044 7H14.25A6.25 6.25 0 0 1 8 35.75zm23.707 12.895a1 1 0 0 0-1.414 0l-3 3a1 1 0 0 0 0 1.414l3 3a1 1 0 1 0 1.414-1.414L30.414 35H36a4 4 0 0 1 4 4a1 1 0 1 0 2 0a6 6 0 0 0-6-6h-5.586l1.293-1.293a1 1 0 0 0 0-1.414M39 6a3 3 0 0 1 3 3v3.5a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3z");
}

</style>
