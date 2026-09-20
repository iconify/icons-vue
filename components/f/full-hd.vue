<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hymw5m9-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:full-hd" /></template>
<style>
.hymw5m9-a {
  fill: currentColor;
  d: path("M9.5 15H11v-2h1.5v2H14V9h-1.5v2.5H11V9H9.5zm5.5 0h3.5q.425 0 .713-.288T19.5 14v-4q0-.425-.288-.712T18.5 9H15zm1.5-1.5v-3H18v3zM4.5 15H6v-2h2v-1.5H6v-1h2.5V9h-4zM3 20q-.825 0-1.412-.587T1 18V6q0-.825.588-1.412T3 4h18q.825 0 1.413.588T23 6v12q0 .825-.587 1.413T21 20z");
}

</style>
