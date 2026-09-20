<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvf1fkbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fit-screen-outline" /></template>
<style>
.pvf1fkbzj {
  fill: currentColor;
  d: path("M20 9V6h-3V4h3q.825 0 1.413.588T22 6v3zM2 9V6q0-.825.588-1.412T4 4h3v2H4v3zm15 11v-2h3v-3h2v3q0 .825-.587 1.413T20 20zM4 20q-.825 0-1.412-.587T2 18v-3h2v3h3v2zm2-4V8h12v8zm2-2h8v-4H8zm0 0v-4z");
}

</style>
