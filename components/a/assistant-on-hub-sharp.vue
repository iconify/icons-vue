<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p07jluaay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:assistant-on-hub-sharp" /></template>
<style>
.p07jluaay {
  fill: currentColor;
  d: path("M11.038 11.713q.287-.288.287-.713t-.287-.712t-.713-.288t-.712.288t-.288.712t.288.713t.712.287t.713-.288m-3.325 0Q8 11.426 8 11t-.288-.712T7 10t-.712.288T6 11t.288.713T7 12t.713-.288m5.962.288q.425 0 .713-.288t.287-.712t-.288-.712t-.712-.288t-.712.288t-.288.712t.288.713t.712.287m4.038-.288Q18 11.426 18 11t-.288-.712T17 10t-.712.288T16 11t.288.713T17 12t.713-.288M12 20q-2.475 0-4.237-.337T6 18.85V18H2V4h20v14h-4v.85q0 .475-1.763.813T12 20");
}

</style>
