<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk_3ebciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-justify-space-between-rounded" /></template>
<style>
.vk_3ebciy {
  fill: currentColor;
  d: path("M20.288 21.713Q20 21.425 20 21v-4h-2q-.425 0-.712-.288T17 16V8q0-.425.288-.712T18 7h2V3q0-.425.288-.712T21 2t.713.288T22 3v18q0 .425-.288.713T21 22t-.712-.288M3 22q-.425 0-.712-.288T2 21V3q0-.425.288-.712T3 2t.713.288T4 3v4h2q.425 0 .713.288T7 8v8q0 .425-.288.713T6 17H4v4q0 .425-.288.713T3 22");
}

</style>
