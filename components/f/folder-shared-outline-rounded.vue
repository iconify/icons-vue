<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk7aqz16l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-shared-outline-rounded" /></template>
<style>
.rk7aqz16l {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h5.175q.4 0 .763.15t.637.425L12 6h8q.825 0 1.413.588T22 8v10q0 .825-.587 1.413T20 20zm0-2h16V8h-8.825l-2-2H4zm0 0V6zm7-1h8v-.55q0-1.125-1.1-1.787T15 14t-2.9.663T11 16.45zm5.413-4.587Q17 11.825 17 11t-.587-1.412T15 9t-1.412.588T13 11t.588 1.413T15 13t1.413-.587");
}

</style>
