<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz05094zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fax" /></template>
<style>
.sz05094zv {
  fill: currentColor;
  d: path("M7.154 19.5v-10H8.5V4.846h9V9.5H19q1.042 0 1.77.73q.73.728.73 1.77v7.5zm-2.71 1q.817 0 1.379-.563t.561-1.38v-8.115q0-.815-.563-1.379Q5.257 8.5 4.44 8.5t-1.379.563t-.561 1.38v8.115q0 .816.564 1.379t1.38.563M9.5 9.5h7V5.846h-7zm6.636 4.213q.287-.288.287-.713t-.287-.712t-.713-.288t-.712.288t-.288.712t.288.713t.712.287t.713-.288m3 0q.287-.287.287-.712t-.287-.712t-.713-.288t-.712.288t-.288.712t.288.713t.712.287t.713-.288m-3 3q.287-.287.287-.712t-.287-.713t-.713-.287t-.712.287t-.288.713t.288.712t.712.288t.713-.288m3 0q.287-.287.287-.712t-.287-.713t-.713-.287t-.712.287t-.288.713t.288.712t.712.288t.713-.288M9.423 17h4v-5h-4z");
}

</style>
