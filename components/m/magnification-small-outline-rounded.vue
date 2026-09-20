<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5glj1bnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:magnification-small-outline-rounded" /></template>
<style>
.p5glj1bnz {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v12q0 .825-.587 1.413T20 20zm0-2h16V6H4zm0 0V6zm4.413-7.587Q9 9.825 9 9t-.587-1.412T7 7t-1.412.588T5 9t.588 1.413T7 11t1.413-.587");
}

</style>
