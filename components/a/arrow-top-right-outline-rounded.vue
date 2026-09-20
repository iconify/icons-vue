<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpjd2usno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-top-right-outline-rounded" /></template>
<style>
.bpjd2usno {
  fill: currentColor;
  d: path("M16.175 10H7v9q0 .425-.288.713T6 20t-.712-.288T5 19v-9q0-.825.588-1.412T7 8h9.175L13.3 5.125q-.3-.3-.312-.712t.287-.713t.713-.3t.712.3l4.6 4.6q.15.15.213.325t.062.375t-.062.375t-.213.325l-4.625 4.625q-.3.3-.7.288t-.7-.313q-.275-.3-.288-.7t.288-.7z");
}

</style>
