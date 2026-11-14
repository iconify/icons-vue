<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g7n4fob9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ac-dry-mode" /></template>
<style>
.g7n4fob9h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q1.76 0 3.005 1.245T22.25 6.5v1q0 1.76-1.245 3.005T18 11.75H6q-1.76 0-3.005-1.245T1.75 7.5v-1q0-1.76 1.245-3.005T6 2.25m0 5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.25 8t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T6 8.75h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T18.75 8t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T18 7.25zm5.47 6.22q.105-.106.243-.163T12 13.25t.287.057t.243.163q3.22 3.219 3.22 5.03q0 3.75-3.75 3.75T8.25 18.5q0-1.811 3.22-5.03");
}

</style>
