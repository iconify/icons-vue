<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p57oy4cdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:airplane-ticket-sharp" /></template>
<style>
.p57oy4cdw {
  fill: currentColor;
  d: path("M3 19v-4.192q.883-.327 1.441-1.088Q5 12.96 5 12t-.559-1.72T3 9.192V5h18v14zm5.927-3.58l8.708-2.312q.336-.081.533-.367q.198-.285.117-.603q-.081-.317-.38-.447q-.3-.13-.616-.049l-2.527.689l-4-3.75l-1.054.234l2.4 4.2l-2.746.677l-1.25-.95l-.604.173z");
}

</style>
