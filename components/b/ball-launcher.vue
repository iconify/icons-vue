<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be5u1ihrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-launcher" /></template>
<style>
.be5u1ihrf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.25 5q0-3.25 3.25-3.25q1.346 0 2.298.952T21.75 5t-.952 2.298t-2.298.952q-3.25 0-3.25-3.25M3.708 12.944q-2.048 1.433-.615 3.481l.573.819q.587.838 1.59 1.024q.038.867.328 1.482H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h11q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 19.75h-2.584q.334-.708.334-1.75q0-1.837-1.039-2.636l2.581-1.808q2.048-1.433.615-3.481l-.573-.819q-.594-.849-1.615-1.029t-1.868.415z");
}

</style>
