<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2wmi1omx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-car" /></template>
<style>
.g2wmi1omx {
  fill: currentColor;
  d: path("M1 20v-3h2V6q0-.825.588-1.412T5 4h13q.825 0 1.413.588T20 6v3h-7.65q-.925 0-1.712.488T9.55 10.85L8 15.3V20zm9.65 2q-.275 0-.462-.187T10 21.35v-5.575l1.425-4.1q.125-.3.375-.488t.575-.187h7.25q.325 0 .575.188t.375.487l1.425 4.1v5.575q0 .275-.187.463T21.35 22h-.7q-.275 0-.462-.187T20 21.35v-.85h-8v.85q0 .275-.187.463T11.35 22zm1.2-7h8.3l-.875-2.5h-6.55zm1.65 3.75q.425 0 .713-.288t.287-.712t-.288-.712t-.712-.288t-.712.288t-.288.712t.288.713t.712.287m5 0q.425 0 .713-.288t.287-.712t-.288-.712t-.712-.288t-.712.288t-.288.712t.288.713t.712.287");
}

</style>
