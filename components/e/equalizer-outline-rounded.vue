<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fncahsbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:equalizer-outline-rounded" /></template>
<style>
.fncahsbzj {
  fill: currentColor;
  d: path("M4.588 19.413Q4 18.825 4 18v-4q0-.825.588-1.412T6 12t1.413.588T8 14v4q0 .825-.587 1.413T6 20t-1.412-.587M12 20q-.825 0-1.412-.587T10 18V6q0-.825.588-1.412T12 4t1.413.588T14 6v12q0 .825-.587 1.413T12 20m4.588-.587Q16 18.825 16 18v-7q0-.825.588-1.412T18 9t1.413.588T20 11v7q0 .825-.587 1.413T18 20t-1.412-.587");
}

</style>
