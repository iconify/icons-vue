<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3ksa1b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blacks-adjust" /></template>
<style>
.g3ksa1b7v {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-1.76 1.245-3.005T6 7.75t3.005 1.245T10.25 12t-1.245 3.005T6 16.25t-3.005-1.245T1.75 12M20 9.75h-6.25q-2.25 0-2.25 2.25t2.25 2.25H20q2.25 0 2.25-2.25T20 9.75m-13.99 1.5H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
