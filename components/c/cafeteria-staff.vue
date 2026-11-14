<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lezyf-b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cafeteria-staff" /></template>
<style>
.lezyf-b-e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 5.75Q9.75 3.5 12 3.5t2.25 2.25q0 .574-.147 1.002q2.095.529 3.731 2.164q2.416 2.417 2.416 5.834q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141q-.014-.072-.014-.146q0-3.417 2.416-5.834q1.636-1.635 3.731-2.164q-.147-.428-.147-1.002m-6 11q-.828 0-1.414.586T1.75 18.75q0 2 2 2h16.5q2 0 2-2t-2-2z");
}

</style>
