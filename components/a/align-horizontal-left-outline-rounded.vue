<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5-pvacwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-horizontal-left-outline-rounded" /></template>
<style>
.b5-pvacwv {
  fill: currentColor;
  d: path("M3 22q-.425 0-.712-.288T2 21V3q0-.425.288-.712T3 2t.713.288T4 3v18q0 .425-.288.713T3 22m4.5-5q-.625 0-1.062-.437T6 15.5t.438-1.062T7.5 14h7q.625 0 1.063.438T16 15.5t-.437 1.063T14.5 17zm0-7q-.625 0-1.062-.437T6 8.5t.438-1.062T7.5 7h13q.625 0 1.063.438T22 8.5t-.437 1.063T20.5 10z");
}

</style>
