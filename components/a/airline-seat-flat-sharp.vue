<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijmlq0b5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airline-seat-flat-sharp" /></template>
<style>
.ijmlq0b5t {
  fill: currentColor;
  d: path("M9 14V7h13v7zm-7 3v-2h20v2zm.875-3.875Q2 12.25 2 11t.875-2.125T5 8t2.125.875T8 11t-.875 2.125T5 14t-2.125-.875");
}

</style>
