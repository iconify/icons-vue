<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r3ewopbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cassette-deck" /></template>
<style>
.r3ewopbho {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 3.75h12q1.76 0 3.005 1.245T22.25 8v8q0 1.76-1.245 3.005T18 20.25H6q-1.76 0-3.005-1.245T1.75 16V8q0-1.76 1.245-3.005T6 3.75m9.5 3h-7q-3.75 0-3.75 3.75t3.75 3.75h7q3.75 0 3.75-3.75T15.5 6.75m1.5 9H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h10q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T17 15.75");
}

</style>
