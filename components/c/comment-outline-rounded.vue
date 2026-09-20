<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mltbkhbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comment-outline-rounded" /></template>
<style>
.mltbkhbiw {
  fill: currentColor;
  d: path("M7 14h10q.425 0 .713-.288T18 13t-.288-.712T17 12H7q-.425 0-.712.288T6 13t.288.713T7 14m0-3h10q.425 0 .713-.288T18 10t-.288-.712T17 9H7q-.425 0-.712.288T6 10t.288.713T7 11m0-3h10q.425 0 .713-.288T18 7t-.288-.712T17 6H7q-.425 0-.712.288T6 7t.288.713T7 8M4 18q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v15.575q0 .675-.612.938T20.3 20.3L18 18zm14.85-2L20 17.125V4H4v12zM4 16V4z");
}

</style>
