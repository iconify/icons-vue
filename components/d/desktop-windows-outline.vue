<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3ig2vb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-windows-outline" /></template>
<style>
.i3ig2vb5x {
  fill: currentColor;
  d: path("M8 21v-2h2v-2H4q-.825 0-1.412-.587T2 15V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v10q0 .825-.587 1.413T20 17h-6v2h2v2zm-4-6h16V5H4zm0 0V5z");
}

</style>
