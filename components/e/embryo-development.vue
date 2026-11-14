<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqp025ihm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:embryo-development" /></template>
<style>
.tqp025ihm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m8.75-6.75Q6.75 5.25 6.75 9t3.75 3.75q2.32 0 3.205-1.435Q15 12.161 15 13.906q0 2.071-2.099 2.351q-.976.122-1.277-.329q-.196-.295.156-.648q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T11.25 14t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-1.223 1.222-.344 2.54q.815 1.222 2.723.983q3.401-.453 3.401-3.837q0-2.823-2.305-4.05q.055-.4.055-.856q0-3.75-3.75-3.75");
}

</style>
