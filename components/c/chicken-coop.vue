<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx23w6bht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chicken-coop" /></template>
<style>
.qx23w6bht {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.731 8.379q-.981.751-.981 1.986v3.885q0 2.5 2.5 2.5V21q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T6.75 21v-4.25h7.023l7.311 4.874q.061.041.13.069q.068.028.14.043t.147.014q.074 0 .146-.015q.073-.014.141-.042t.129-.07t.114-.093q.052-.053.093-.114t.069-.13t.043-.14q.014-.073.014-.147t-.015-.146q-.014-.073-.042-.141t-.07-.129t-.093-.114q-.053-.052-.114-.093l-5.439-3.626h2.273q2.5 0 2.5-2.5v-3.885q0-1.235-.981-1.986l-6.75-5.162q-1.519-1.161-3.038 0z");
}

</style>
