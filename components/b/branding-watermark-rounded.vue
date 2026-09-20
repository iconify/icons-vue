<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc4v-a4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:branding-watermark-rounded" /></template>
<style>
.ydc4v-a4k {
  fill: currentColor;
  d: path("M11 17h7q.425 0 .713-.288T19 16v-4q0-.425-.288-.712T18 11h-7q-.425 0-.712.288T10 12v4q0 .425.288.713T11 17m-7 3q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
