<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-wtc-dah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cards-stack" /></template>
<style>
.o-wtc-dah {
  fill: currentColor;
  d: path("M5.45 20.975Q4.625 21.1 4 20.6t-.75-1.325L2.025 10.35q-.125-.8.388-1.45t1.312-.775H4V14q0 1.65 1.175 2.825T8 18h11q-.2.525-.612.888t-1.013.437zM8 16.1q-.825 0-1.412-.587T6 14.1V5q0-.825.588-1.412T8 3h12q.825 0 1.413.588T22 5v9.1q0 .825-.587 1.413T20 16.1zM10 9h8V7h-8zm0 3h5v-2h-5z");
}

</style>
