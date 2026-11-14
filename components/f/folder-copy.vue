<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqhi0jbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:folder-copy" /></template>
<style>
.oqhi0jbtp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 5.5V17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141T4.25 17V5.5q0-.75.75-.75h2.689L8.97 6.03q.105.106.243.163t.287.057H16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T16 4.75H9.811L8.53 3.47q-.105-.106-.243-.163T8 3.25H5q-2.25 0-2.25 2.25M8.5 7.75q-2.25 0-2.25 2.25v9q0 2.25 2.25 2.25h11q2.25 0 2.25-2.25v-7.5q0-2.25-2.25-2.25h-6.189L12.03 7.97q-.105-.106-.243-.163T11.5 7.75z");
}

</style>
