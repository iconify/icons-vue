<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cep_peb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:collapse-content-rounded" /></template>
<style>
.cep_peb5q {
  fill: currentColor;
  d: path("M9 15H6q-.425 0-.712-.288T5 14t.288-.712T6 13h4q.425 0 .713.288T11 14v4q0 .425-.288.713T10 19t-.712-.288T9 18zm6-6h3q.425 0 .713.288T19 10t-.288.713T18 11h-4q-.425 0-.712-.288T13 10V6q0-.425.288-.712T14 5t.713.288T15 6z");
}

</style>
