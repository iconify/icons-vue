<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx3ahtbtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chair-alt-outline" /></template>
<style>
.xx3ahtbtk {
  fill: currentColor;
  d: path("M5 21v-7q0-.825.588-1.412T7 12h1v-2H7q-.825 0-1.412-.587T5 8V5q0-.825.588-1.412T7 3h10q.825 0 1.413.588T19 5v3q0 .825-.587 1.413T17 10h-1v2h1q.825 0 1.413.588T19 14v7h-2v-3H7v3zM7 8h10V5H7zm3 4h4v-2h-4zm-3 4h10v-2H7zm0-8V5zm0 8v-2z");
}

</style>
