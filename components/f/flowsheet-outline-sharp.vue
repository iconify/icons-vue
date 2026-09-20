<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hzg42catf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flowsheet-outline-sharp" /></template>
<style>
.hzg42catf {
  fill: currentColor;
  d: path("M4 12v6V6zm10 9q.425 0 .713-.288T15 20t-.288-.712T14 19t-.712.288T13 20t.288.713T14 21m6-10q.425 0 .713-.288T21 10t-.288-.712T20 9t-.712.288T19 10t.288.713T20 11M6 11h5V9H6zm0 4h5v-2H6zm-4 5V4h20v2H4v12h5v2zm9.875 2.125Q11 21.25 11 20q0-.975.563-1.75T13 17.175V14h6v-1.175q-.875-.3-1.437-1.075T17 10q0-1.25.875-2.125T20 7t2.125.875T23 10q0 .975-.562 1.75T21 12.825V16h-6v1.175q.875.3 1.438 1.075T17 20q0 1.25-.875 2.125T14 23t-2.125-.875");
}

</style>
