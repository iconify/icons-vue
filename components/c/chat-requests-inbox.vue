<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_eok0zod"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-requests-inbox" /></template>
<style>
.v_eok0zod {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5v15q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.11 0 .216-.032q.105-.031.197-.092q.092-.06.162-.145t.114-.186l3-7q.061-.141.061-.295q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-1.25V7q0-2.25-2.25-2.25h-7.189L9.03 2.97q-.105-.106-.243-.163T8.5 2.75H4Q1.75 2.75 1.75 5M6 12.25q-.104 0-.205.029q-.1.028-.189.083t-.16.132t-.117.171L3.25 16.823V5q0-.75.75-.75h4.189L9.97 6.03q.105.106.243.163t.287.057H18q.75 0 .75.75v5.25h-1.5V9.5q0-1.75-1.75-1.75h-7q-1.75 0-1.75 1.75v2.75zm2.25-2.483v2.483h7.5V9.767l-3.464 1.427q-.138.056-.286.056t-.286-.056zm4.816-.517L12 9.689l-1.066-.439z");
}

</style>
