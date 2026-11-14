<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ta3onzb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-card" /></template>
<style>
.ta3onzb3k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.75h12q1.76 0 3.005 1.245T22.25 7v10q0 1.76-1.245 3.005T18 21.25H6q-1.76 0-3.005-1.245T1.75 17V7q0-1.76 1.245-3.005T6 2.75m.5 4q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014zm2 3.5q-2.25 0-2.25 2.25V16q0 2.25 2.25 2.25h7q2.25 0 2.25-2.25v-3.5q0-2.25-2.25-2.25z");
}

</style>
