<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op6k_923d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:aromatherapy" /></template>
<style>
.op6k_923d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 6.879q.5.56.5 1.621q0 .65-.188 1.113q.924.375 1.687 1.138q1.501 1.501 1.501 3.624v2.75q0 2.123-1.501 3.624t-3.624 1.501h-2.25q-2.123 0-3.624-1.501T5.75 17.125v-2.75q0-2.123 1.501-3.624q.763-.763 1.687-1.138Q8.75 9.15 8.75 8.5q0-1.061.5-1.621V4.5q0-2.75 2.75-2.75t2.75 2.75zm-4-.622q.121-.007.25-.007h2q.129 0 .25.007V4.5q0-1.25-1.25-1.25T10.75 4.5zm-2 11.993q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T9.5 19q5.75 0 5.75-5.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-5.75 0-5.75 5.75");
}

</style>
