<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt4two81n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheese-counter" /></template>
<style>
.vt4two81n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 11.5v6.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T1.75 19t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-.25V11.5q-.001-3.831-2.71-6.539T12 2.253T5.46 4.961T2.75 11.5m1.5 6.75V11.5q.001-3.209 2.271-5.478T12 3.753t5.479 2.269T19.75 11.5v6.75zm7.75-1.5h3.5q2.25 0 2.25-2.25v-2.236q0-1.339-1.176-1.977q-1.177-.639-2.3.09l-3.491 2.269q-1.398.908-.924 2.507q.474 1.598 2.141 1.597");
}

</style>
