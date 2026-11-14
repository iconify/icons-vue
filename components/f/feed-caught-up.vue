<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xatz_rnlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:feed-caught-up" /></template>
<style>
.xatz_rnlx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.75 1.75h-3.5q-2.485 0-4.243 1.757Q4.25 5.265 4.25 7.75v8.5q0 2.485 1.757 4.243q1.758 1.757 4.243 1.757h3.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-8.5q0-2.485-1.757-4.243Q16.235 1.75 13.75 1.75m-2.775 12.415l4.721-5.171q.05-.054.109-.098q.06-.044.127-.075q.067-.032.138-.049t.146-.021q.074-.004.147.008q.073.011.142.036q.07.025.133.063t.118.088q.11.101.173.236t.07.284t-.044.289t-.151.251l-5.25 5.75l-.024.024q-.052.053-.113.094t-.13.069t-.141.043T11 16t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-3-3q-.106-.105-.163-.243t-.057-.287t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T8 11.5t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
