<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8hy_mypk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:baby-changing-station-outline-sharp" /></template>
<style>
.i8hy_mypk {
  fill: currentColor;
  d: path("M3 22V12l1.575-4.625q.2-.65.75-1.012T6.5 6q.2 0 .4.038t.4.137L11.45 8H14v2h-3L8.3 8.825L7 12.75V22zm6-3v-2h12v2zm10.5-3q-.625 0-1.062-.437T18 14.5t.438-1.062T19.5 13t1.063.438T21 14.5t-.437 1.063T19.5 16M11 16v-3H9v-2h4v2h2v-2h2v5zM8 5q-.825 0-1.412-.587T6 3t.588-1.412T8 1t1.413.588T10 3t-.587 1.413T8 5");
}

</style>
