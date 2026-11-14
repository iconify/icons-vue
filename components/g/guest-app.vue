<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op8d8zmwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:guest-app" /></template>
<style>
.op8d8zmwg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.875 1.75h4.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-4.25q-2.123 0-3.624-1.501T4.75 17.125V6.875q0-2.123 1.501-3.624T9.875 1.75m.625 3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014zm-2.091 7.781h-.001q-.658.659-.658 1.59V16.5q0 2.25 2.25 2.25h4q.932 0 1.591-.659t.659-1.591v-2.379q0-.931-.659-1.59l-2-2q-.659-.66-1.591-.66t-1.591.66z");
}

</style>
