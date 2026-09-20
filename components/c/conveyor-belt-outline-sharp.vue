<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="curxw_44s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:conveyor-belt-outline-sharp" /></template>
<style>
.curxw_44s {
  fill: currentColor;
  d: path("M5 21q-1.25 0-2.125-.875T2 18t.875-2.125T5 15h14q1.25 0 2.125.875T22 18t-.875 2.125T19 21zm0-2h14q.425 0 .713-.288T20 18t-.288-.712T19 17H5q-.425 0-.712.288T4 18t.288.713T5 19m4-6V3h10v10zm2-2h6V5h-6zm-9-.05V9.025h4.925v1.925zM12 8h4V6.025h-4zM4 8h2.925V6.025H4zm7 3V5z");
}

</style>
