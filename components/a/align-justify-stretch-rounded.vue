<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6_94qbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-stretch-rounded" /></template>
<style>
.z6_94qbzc {
  fill: currentColor;
  d: path("M20.288 21.713Q20 21.425 20 21V3q0-.425.288-.712T21 2t.713.288T22 3v18q0 .425-.288.713T21 22t-.712-.288M3 22q-.425 0-.712-.288T2 21V3q0-.425.288-.712T3 2t.713.288T4 3v18q0 .425-.288.713T3 22m11-12q-.425 0-.712-.288T13 9V8q0-.425.288-.712T14 7h3q.425 0 .713.288T18 8v1q0 .425-.288.713T17 10zm-7 0q-.425 0-.712-.288T6 9V8q0-.425.288-.712T7 7h3q.425 0 .713.288T11 8v1q0 .425-.288.713T10 10zm7 7q-.425 0-.712-.288T13 16v-1q0-.425.288-.712T14 14h3q.425 0 .713.288T18 15v1q0 .425-.288.713T17 17zm-7 0q-.425 0-.712-.288T6 16v-1q0-.425.288-.712T7 14h3q.425 0 .713.288T11 15v1q0 .425-.288.713T10 17z");
}

</style>
