<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm_4svbgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:direct-air-capture" /></template>
<style>
.hm_4svbgq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 1.75h-6q-1.76 0-3.005 1.245T7.75 6v4.189l-.97-.969q-.052-.053-.113-.094t-.13-.069t-.141-.043T6.25 9t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T5.5 9.75t.057.287t.163.243l.969.97H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4.189l-.969.97q-.106.105-.163.243t-.057.287t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l.97-.969V18q0 1.76 1.245 3.005T12 22.25h6q1.76 0 3.005-1.245T22.25 18V6q0-1.76-1.245-3.005T18 1.75m-6.182 7.068Q13.136 7.5 15 7.5t3.182 1.318T19.5 12t-1.318 3.182T15 16.5t-3.182-1.318T10.5 12t1.318-3.182");
}

</style>
