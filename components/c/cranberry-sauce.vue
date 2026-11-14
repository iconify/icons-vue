<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqur45b7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cranberry-sauce" /></template>
<style>
.yqur45b7z {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.752 7.331Q8.836 4.25 12 4.25q3.148 0 3.247 3.05q.352-.05.753-.05q3.25 0 3.25 3.25q0 1.042-.334 1.75H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q-.001 3.075-2.948 5.203q-2.833 2.045-6.802 2.045t-6.802-2.045Q2.251 16.075 2.25 13q0-.074.014-.146t.043-.141q.028-.068.069-.129q.041-.062.093-.114q.053-.052.114-.093t.13-.07t.14-.043q.073-.014.147-.014h2.084q-.334-.708-.334-1.75q0-3.25 3.25-3.25q.393 0 .752.081m2.493 3.369q-.047.859-.499 1.55h2.338q-.301-.639-.331-1.55q-.352.05-.753.05q-.403 0-.755-.05");
}

</style>
