<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk6s7lbql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:backpack-rounded" /></template>
<style>
.gk6s7lbql {
  fill: currentColor;
  d: path("M6 22q-.825 0-1.412-.587T4 20V8q0-1.4.85-2.45T7 4.15V3q0-.425.288-.713T8 2h1q.425 0 .713.288T10 3v1h4V3q0-.425.288-.712T15 2h1q.425 0 .713.288T17 3v1.15q1.3.35 2.15 1.4T20 8v12q0 .825-.587 1.413T18 22zm8.5-8v1q0 .425.288.713T15.5 16t.713-.288T16.5 15v-2q0-.425-.288-.712T15.5 12h-7q-.425 0-.712.288T7.5 13t.288.713T8.5 14z");
}

</style>
