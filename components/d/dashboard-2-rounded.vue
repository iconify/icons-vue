<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4sc91b7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-2-rounded" /></template>
<style>
.w4sc91b7g {
  fill: currentColor;
  d: path("M16 20q-.425 0-.712-.288T15 19v-5q0-.425.288-.712T16 13h5q.425 0 .713.288T22 14v5q0 .425-.288.713T21 20zm-4-9q-.425 0-.712-.288T11 10V5q0-.425.288-.712T12 4h9q.425 0 .713.288T22 5v5q0 .425-.288.713T21 11zm-9 9q-.425 0-.712-.288T2 19v-5q0-.425.288-.712T3 13h9q.425 0 .713.288T13 14v5q0 .425-.288.713T12 20zm0-9q-.425 0-.712-.288T2 10V5q0-.425.288-.712T3 4h5q.425 0 .713.288T9 5v5q0 .425-.288.713T8 11z");
}

</style>
