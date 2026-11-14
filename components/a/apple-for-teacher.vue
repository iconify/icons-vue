<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6iwwsbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:apple-for-teacher" /></template>
<style>
.s6iwwsbrq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.124 2.584q1.313-.54 3.209-.329q.073.008.144.03t.135.058t.121.083t.103.105t.08.124q.034.065.054.136q.021.071.027.145q.007.073-.002.147l-.003.023q-.247 1.735-1.844 2.534q-.306.153-.642.258q.24.06.481.14l.019.007q4.813 1.75 3.225 8.125q-.605 2.81-2.345 4.876Q16.03 21.25 14 21.25q-.519 0-1.279-.304q-.49-.196-.721-.196t-.721.196q-.76.304-1.279.304q-2.03 0-3.886-2.204q-1.74-2.066-2.345-4.876q-1.588-6.375 3.225-8.125l.019-.007q2.207-.735 4.334.238q.431-2.584 2.781-3.927q.061-.035.128-.058t.137-.033t.14-.007t.139.019t.133.045t.123.069t.107.091q.05.05.089.109M13.013 5.82q-.059.168-.104.345q.238-.097.478-.173l-.021-.004q-.199-.036-.353-.168");
}

</style>
