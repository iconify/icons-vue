<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ih5513gbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:forum" /></template>
<style>
.ih5513gbo {
  fill: currentColor;
  d: path("M7 18q-.425 0-.712-.288T6 17v-2h13V6h2q.425 0 .713.288T22 7v15l-4-4zm-5-1V3q0-.425.288-.712T3 2h13q.425 0 .713.288T17 3v9q0 .425-.288.713T16 13H6z");
}

</style>
