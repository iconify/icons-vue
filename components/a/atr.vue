<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijxxf_b0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:atr" /></template>
<style>
.ijxxf_b0c {
  fill: currentColor;
  d: path("M6 20q-1.25 0-2.125-.875T3 17t.875-2.125T6 14t2.125.875T9 17t-.875 2.125T6 20m12 0q-1.25 0-2.125-.875T15 17t.875-2.125T18 14t2.125.875T21 17t-.875 2.125T18 20M9.875 9.125Q9 8.25 9 7t.875-2.125T12 4t2.125.875T15 7t-.875 2.125T12 10t-2.125-.875");
}

</style>
