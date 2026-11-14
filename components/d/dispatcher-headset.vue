<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2fpwwp9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dispatcher-headset" /></template>
<style>
.k2fpwwp9a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 9.5v1.81q-2 .345-2 2.69v3q0 2.377 2.055 2.7q.43 2.55 4.195 2.55h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-3q-2.164 0-2.625-1.084Q7.75 19.271 7.75 17v-3q0-2.345-2-2.69V9.5q0-2.589 1.831-4.419Q9.411 3.25 12 3.25t4.419 1.831T18.25 9.5v1.81q-2 .345-2 2.69v3q0 2.75 2.75 2.75T21.75 17v-3q0-2.345-2-2.69V9.5q0-3.21-2.27-5.48T12 1.75T6.52 4.02T4.25 9.5");
}

</style>
