<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ukt3_b9wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:fluid-rounded" /></template>
<style>
.ukt3_b9wa {
  fill: currentColor;
  d: path("M13 23q-.825 0-1.412-.587T11 21v-2.075q-2.575-.35-4.288-2.312T5 12V3q0-.825.588-1.412T7 1h10q.825 0 1.413.588T19 3v9q0 2.65-1.713 4.613T13 18.925V21h5q.425 0 .713.288T19 22t-.288.713T18 23zm.75-10h3.15q.05-.25.075-.488T17 12v-1h-3q-.425 0-.712-.288T13 10t.288-.712T14 9h3V7h-4q-.425 0-.712-.288T12 6t.288-.712T13 5h4V3H7v8h2.75q.825 0 1.563.375T12.55 12.4q.2.275.525.438t.675.162");
}

</style>
