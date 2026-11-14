<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvqf1fbrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-turn-up-left" /></template>
<style>
.cvqf1fbrl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.97 8.47l4-4q.105-.106.243-.163T7.5 4.25t.287.057t.243.163h.001l3.999 4q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094L8.25 6.811V14q0 1.76 1.245 3.005T12.5 18.25h8q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-8q-2.382 0-4.066-1.684T6.75 14V6.811L4.03 9.53q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.106-.105-.163-.243T2.75 9t.057-.287t.163-.243");
}

</style>
