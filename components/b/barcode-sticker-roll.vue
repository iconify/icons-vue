<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rit4qib2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:barcode-sticker-roll" /></template>
<style>
.rit4qib2s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-1.968 1.391-3.359T6.5 7.25t3.359 1.391T11.25 12q0 1.891-1.285 3.25h1.611q-.076-.337-.076-.75v-3q0-2.25 2.25-2.25h.75q2.25 0 2.25 2.25v3q0 .413-.076.75h.402Q17 14.913 17 14.5v-3q0-2.25 2.25-2.25H20q2.25 0 2.25 2.25v3q0 .599-.159 1.038q.077.099.118.218q.041.118.041.244q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-1.968 0-3.359-1.391T1.75 12m2.75 0q0-2 2-2q.828 0 1.414.586T8.5 12t-.586 1.414T6.5 14q-2 0-2-2");
}

</style>
