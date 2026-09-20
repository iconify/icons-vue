<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4vblbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-range-rounded" /></template>
<style>
.ho4vblbgj {
  fill: currentColor;
  d: path("M5.825 13L7.7 14.875q.275.3.288.713T7.7 16.3t-.7.3t-.7-.3l-3.6-3.6q-.15-.15-.213-.325T2.426 12t.063-.375t.212-.325l3.6-3.6q.3-.3.7-.3t.7.3t.3.713t-.3.712L5.825 11h12.35L16.3 9.125q-.275-.3-.287-.712T16.3 7.7t.7-.3t.7.3l3.6 3.6q.15.15.213.325t.062.375t-.062.375t-.213.325l-3.6 3.6q-.3.3-.7.3t-.7-.3t-.3-.712t.3-.713L18.175 13z");
}

</style>
