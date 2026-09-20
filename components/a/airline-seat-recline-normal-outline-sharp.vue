<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmzph5b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-recline-normal-outline-sharp" /></template>
<style>
.jmzph5b9m {
  fill: currentColor;
  d: path("M6 20V7h2v11h7v2zm5.5-14q-.825 0-1.412-.587T9.5 4t.588-1.412T11.5 2t1.413.588T13.5 4t-.587 1.413T11.5 6M16 22v-5H9V9.5q0-1.05.725-1.775T11.5 7t1.775.725T14 9.5V14h4v8z");
}

</style>
