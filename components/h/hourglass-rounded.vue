<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt_h0acge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hourglass-rounded" /></template>
<style>
.bt_h0acge {
  fill: currentColor;
  d: path("M5 22q-.425 0-.712-.288T4 21t.288-.712T5 20h1v-3q0-1.525.713-2.863T8.7 12q-1.275-.8-1.987-2.137T6 7V4H5q-.425 0-.712-.288T4 3t.288-.712T5 2h14q.425 0 .713.288T20 3t-.288.713T19 4h-1v3q0 1.525-.712 2.863T15.3 12q1.275.8 1.988 2.138T18 17v3h1q.425 0 .713.288T20 21t-.288.713T19 22z");
}

</style>
