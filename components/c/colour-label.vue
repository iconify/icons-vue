<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnbms6led"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-label" /></template>
<style>
.jnbms6led {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.75h7.25q2.123 0 3.624 1.501t1.501 3.624v5.676q-.364-.051-.75-.051q-2.071 0-3.536 1.464Q13.5 16.429 13.5 18.5q0 .937.3 1.75H6.875q-2.123 0-3.624-1.501q-.719-.72-1.094-1.582q.161.083.343.083q.149 0 .287-.057t.243-.163l4.47-4.469l4.47 4.469q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-5-5q-.105-.106-.243-.163T7.5 10.75t-.287.057t-.243.163l-5 5q-.076.076-.128.17q-.092-.489-.092-1.015v-7.25q0-2.123 1.501-3.624T6.875 2.75M11 8.5q0 2.5 2.5 2.5T16 8.5T13.5 6T11 8.5m3.75 10q0-3.75 3.75-3.75t3.75 3.75t-3.75 3.75t-3.75-3.75m1.5 0q0 2.25 2.25 2.25t2.25-2.25t-2.25-2.25t-2.25 2.25m2.25-1q.093 0 .178.009q-.355.665-.929 1.24q-.093.093-.189.181q-.06-.185-.06-.43q0-1 1-1");
}

</style>
