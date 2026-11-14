<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knb_tebww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:birthday-offer" /></template>
<style>
.knb_tebww {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.125 5.813q0 1.5 1.125 1.839v2.598H8q-1.76 0-3.005 1.245T3.75 14.5v.5q0-.074.014-.147q.015-.072.043-.14t.07-.13t.093-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h15q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.052-.052-.093-.113q-.042-.062-.07-.13t-.043-.14Q3.75 15.074 3.75 15v2q0 1.76 1.245 3.005T8 21.25h8q1.76 0 3.005-1.245T20.25 17v-2.5q0-1.76-1.245-3.005T16 10.25h-3.25V7.652q1.125-.339 1.125-1.839T12.53 2.97q-.105-.106-.243-.163T12 2.75t-.287.057t-.243.163q-1.345 1.344-1.345 2.843");
}

</style>
