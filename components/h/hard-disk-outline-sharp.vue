<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb-qbggan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hard-disk-outline-sharp" /></template>
<style>
.lb-qbggan {
  fill: currentColor;
  d: path("M4 22V2h16v20zm2-2h12V4H6zm2-2h8v-2H8zm4-4q1.65 0 2.825-1.175T16 10t-1.175-2.825T12 6T9.175 7.175T8 10t1.175 2.825T12 14m0-3q-.425 0-.712-.288T11 10t.288-.712T12 9t.713.288T13 10t-.288.713T12 11m0-1");
}

</style>
