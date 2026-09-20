<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvwj_vbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:download-2-rounded" /></template>
<style>
.pvwj_vbhp {
  fill: currentColor;
  d: path("M5 20h14q.425 0 .713.288T20 21t-.288.713T19 22H5q-.425 0-.712-.288T4 21t.288-.712T5 20m6.563-2.725q-.213-.1-.363-.3l-4.95-6.35q-.375-.5-.1-1.062T7.05 9H9V3q0-.425.288-.712T10 2h4q.425 0 .713.288T15 3v6h1.95q.625 0 .9.563t-.1 1.062l-4.95 6.35q-.15.2-.363.3t-.437.1t-.437-.1");
}

</style>
