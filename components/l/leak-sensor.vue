<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vakj_cksa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leak-sensor" /></template>
<style>
.vakj_cksa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.53 1.97Q15.75 5.189 15.75 7q0 3.75-3.75 3.75T8.25 7q0-1.811 3.22-5.03q.105-.106.243-.163T12 1.75t.287.057t.243.163M12 12q-8.25 0-8.25 3v3q0 .879.708 1.5H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T2.5 21h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.165q.915-.638.915-1.5v-3q0-1.49-2.731-2.309Q15.217 12 12 12m0 7.5q-6.75 0-6.75-1.5v-.987Q7.268 18 12 18q3.217 0 5.519-.691q.707-.212 1.231-.469V18q0 1.5-6.75 1.5");
}

</style>
