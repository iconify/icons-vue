<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dl0e92b5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hmi-panel" /></template>
<style>
.dl0e92b5m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h12q1.76 0 3.005 1.245T22.25 6v4q0 1.76-1.245 3.005T18 14.25h-5.25v6H14q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.25 21t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h1.25v-6H6q-1.76 0-3.005-1.245T1.75 10V6q0-1.76 1.245-3.005T6 1.75M5.5 16q-2.75 0-2.75 2.75T5.5 21.5t2.75-2.75T5.5 16m10.25 2.75q0-2.75 2.75-2.75t2.75 2.75t-2.75 2.75t-2.75-2.75");
}

</style>
