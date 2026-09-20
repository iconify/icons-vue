<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="banakbg0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-plus-rounded" /></template>
<style>
.banakbg0v {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h11q.425 0 .713.288T16 7v2h-1q-.825 0-1.412.588T13 11v2q0 .825.588 1.413T15 15h1v2q0 .425-.288.713T15 18zm14-5h-2q-.425 0-.712-.288T15 12t.288-.712T16 11h2V9q0-.425.288-.712T19 8t.713.288T20 9v2h2q.425 0 .713.288T23 12t-.288.713T22 13h-2v2q0 .425-.288.713T19 16t-.712-.288T18 15z");
}

</style>
