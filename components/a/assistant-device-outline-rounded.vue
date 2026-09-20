<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mc1wd9pmq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:assistant-device-outline-rounded" /></template>
<style>
.mc1wd9pmq {
  fill: currentColor;
  d: path("M9.877 8.877Q9 9.754 9 11t.877 2.123T12 14t2.123-.877T15 11t-.877-2.123T12 8t-2.123.877M12 13q-.825 0-1.412-.587T10 11t.588-1.412T12 9t1.413.588T14 11t-.587 1.413T12 13m4.549 3.549q.22-.22.22-.549t-.22-.549t-.549-.22t-.549.22t-.22.549t.22.549t.549.22t.549-.22M5 18.616V7q0-1.671 1.165-2.835Q7.329 3 9 3h6q1.671 0 2.836 1.165Q19 5.329 19 7v11.616q0 .67-.472 1.143q-.472.472-1.144.472H6.616q-.672 0-1.144-.472T5 18.616M6 18h12V7q0-1.25-.875-2.125T15 4H9q-1.25 0-2.125.875T6 7zm.616 0H18H6zM6 18h12z");
}

</style>
