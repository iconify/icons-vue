<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h13v0eb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bioplastic-leaf" /></template>
<style>
.h13v0eb1n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 2.25h-9q-1.76 0-3.005 1.245T3.25 6.5V18q0 1.76 1.245 3.005T7.5 22.25h9q1.76 0 3.005-1.245T20.75 18V6.5q0-1.76-1.245-3.005T16.5 2.25M20.75 7q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T20 7.75H4q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q3.25 7.074 3.25 7t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T4 6.25h16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M7.25 18q0-8.75 8.75-8.75q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 8.749-8.748 8.75H8q-.147 0-.283-.055t-.24-.158l-.007-.007q-.106-.105-.163-.243T7.25 18");
}

</style>
