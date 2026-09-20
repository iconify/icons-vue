<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq8iygbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-supervised" /></template>
<style>
.lq8iygbec {
  fill: currentColor;
  d: path("M4 20q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h6l2 2h8q.825 0 1.413.588T22 8v3.275q-.875-.625-1.9-.95T17.975 10q-2.95 0-4.962 2.063T11 16.975q0 .8.175 1.55T11.7 20zm10 0v-.55q0-1.125 1.1-1.787T18 17t2.9.663T22 19.45V20zm2.588-4.587Q16 14.825 16 14t.588-1.412T18 12t1.413.588T20 14t-.587 1.413T18 16t-1.412-.587");
}

</style>
