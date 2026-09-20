<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxle2mueu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:door-back" /></template>
<style>
.hxle2mueu {
  fill: currentColor;
  d: path("M3 21v-2h2V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v14h2v2zm7.713-8.287Q11 12.425 11 12t-.288-.712T10 11t-.712.288T9 12t.288.713T10 13t.713-.288");
}

</style>
