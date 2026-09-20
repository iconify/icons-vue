<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wno23xbwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:local-atm" /></template>
<style>
.wno23xbwh {
  fill: currentColor;
  d: path("M11 17h2v-1h1q.425 0 .713-.288T15 15v-3q0-.425-.288-.712T14 11h-3v-1h4V8h-2V7h-2v1h-1q-.425 0-.712.288T9 9v3q0 .425.288.713T10 13h3v1H9v2h2zm-7 3q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20z");
}

</style>
