<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lh6ha11fo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:h-plus-mobiledata-rounded" /></template>
<style>
.lh6ha11fo {
  fill: currentColor;
  d: path("M6 13v3q0 .425-.288.713T5 17t-.712-.288T4 16V8q0-.425.288-.712T5 7t.713.288T6 8v3h6V8q0-.425.288-.712T13 7t.713.288T14 8v8q0 .425-.288.713T13 17t-.712-.288T12 16v-3zm12 0h-1q-.425 0-.712-.288T16 12t.288-.712T17 11h1v-1q0-.425.288-.712T19 9t.713.288T20 10v1h1q.425 0 .713.288T22 12t-.288.713T21 13h-1v1q0 .425-.288.713T19 15t-.712-.288T18 14z");
}

</style>
