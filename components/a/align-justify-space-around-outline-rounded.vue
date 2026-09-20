<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vat9sjbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-space-around-outline-rounded" /></template>
<style>
.vat9sjbng {
  fill: currentColor;
  d: path("M16 17q-.425 0-.712-.288T15 16V8q0-.425.288-.712T16 7h1q.425 0 .713.288T18 8v8q0 .425-.288.713T17 17zm-9 0q-.425 0-.712-.288T6 16V8q0-.425.288-.712T7 7h1q.425 0 .713.288T9 8v8q0 .425-.288.713T8 17zm13.288 4.713Q20 21.425 20 21V3q0-.425.288-.712T21 2t.713.288T22 3v18q0 .425-.288.713T21 22t-.712-.288M3 22q-.425 0-.712-.288T2 21V3q0-.425.288-.712T3 2t.713.288T4 3v18q0 .425-.288.713T3 22");
}

</style>
