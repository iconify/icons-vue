<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqr1bpuww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drag-handle-rounded" /></template>
<style>
.yqr1bpuww {
  fill: currentColor;
  d: path("M5 15q-.425 0-.712-.288T4 14t.288-.712T5 13h14q.425 0 .713.288T20 14t-.288.713T19 15zm0-4q-.425 0-.712-.288T4 10t.288-.712T5 9h14q.425 0 .713.288T20 10t-.288.713T19 11z");
}

</style>
