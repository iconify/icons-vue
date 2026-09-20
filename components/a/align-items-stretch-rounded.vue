<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq7qqwblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-items-stretch-rounded" /></template>
<style>
.aq7qqwblh {
  fill: currentColor;
  d: path("M8 18q-.425 0-.712-.288T7 17V7q0-.425.288-.712T8 6h1q.425 0 .713.288T10 7v10q0 .425-.288.713T9 18zm7 0q-.425 0-.712-.288T14 17V7q0-.425.288-.712T15 6h1q.425 0 .713.288T17 7v10q0 .425-.288.713T16 18zM3 22q-.425 0-.712-.288T2 21t.288-.712T3 20h18q.425 0 .713.288T22 21t-.288.713T21 22zM3 4q-.425 0-.712-.288T2 3t.288-.712T3 2h18q.425 0 .713.288T22 3t-.288.713T21 4z");
}

</style>
