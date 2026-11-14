<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epwngdc2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:airport-lounge" /></template>
<style>
.epwngdc2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.75 13.286q1 .732 1 2.464q0 3-3 3V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T17.25 21v-2.25H6.75V21q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T6 21.75t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 21v-2.25q-1.243 0-2.121-.879q-.879-.878-.879-2.121t.879-2.121q.059-.06.121-.116V10q0-2.75 3.25-2.75h11q3.25 0 3.25 2.75zm-16-.498q.242-.038.5-.038h13.5q.261 0 .5.023V10q0-1.25-1.75-1.25h-11q-1.75 0-1.75 1.25z");
}

</style>
