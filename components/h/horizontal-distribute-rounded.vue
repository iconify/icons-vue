<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pip4rfb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-distribute-rounded" /></template>
<style>
.pip4rfb-s {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21V3q0-.425.288-.712T3 2t.713.288T4 3v18q0 .425-.288.713T3 22m7.938-5.437q-.438-.438-.438-1.063v-7q0-.625.438-1.062T12 7t1.063.438T13.5 8.5v7q0 .625-.437 1.063T12 17t-1.062-.437m9.35 5.15Q20 21.425 20 21V3q0-.425.288-.712T21 2t.713.288T22 3v18q0 .425-.288.713T21 22t-.712-.288");
}

</style>
