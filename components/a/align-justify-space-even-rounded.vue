<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u79igzbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-space-even-rounded" /></template>
<style>
.u79igzbdm {
  fill: currentColor;
  d: path("M15 17q-.425 0-.712-.288T14 16V8q0-.425.288-.712T15 7h1q.425 0 .713.288T17 8v8q0 .425-.288.713T16 17zm-7 0q-.425 0-.712-.288T7 16V8q0-.425.288-.712T8 7h1q.425 0 .713.288T10 8v8q0 .425-.288.713T9 17zm12.288 4.713Q20 21.425 20 21V3q0-.425.288-.712T21 2t.713.288T22 3v18q0 .425-.288.713T21 22t-.712-.288M3 22q-.425 0-.712-.288T2 21V3q0-.425.288-.712T3 2t.713.288T4 3v18q0 .425-.288.713T3 22");
}

</style>
