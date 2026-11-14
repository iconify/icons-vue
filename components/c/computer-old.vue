<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tp_516b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:computer-old" /></template>
<style>
.tp_516b1h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 2.75H7q-1.76 0-3.005 1.245T2.75 7v3.5q0 1.76 1.245 3.005T7 14.75H5q-3.25 0-3.25 3.25T5 21.25h14q3.25 0 3.25-3.25T19 14.75h-2q1.76 0 3.005-1.245T21.25 10.5V7q0-1.76-1.245-3.005T17 2.75m-5.25 3q2.5 0 2.5 2.5v1q0 1.036-.732 1.768t-1.768.732h-3.5q-1.036 0-1.768-.732T5.75 9.25v-1q0-2.5 2.5-2.5zM18 17.25q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13.25 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
