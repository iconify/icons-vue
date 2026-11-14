<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e56oyi3au"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cinema-exit-sign" /></template>
<style>
.e56oyi3au {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 5.25h12q1.76 0 3.005 1.245T22.25 9.5v5q0 1.76-1.245 3.005T18 18.75H6q-1.76 0-3.005-1.245T1.75 14.5v-5q0-1.76 1.245-3.005T6 5.25m11.03 6.22l-3.25-3.25q-.105-.106-.243-.163T13.25 8t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l1.969 1.97H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.25 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7.689l-1.969 1.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094l3.25-3.25q.106-.105.163-.243T17.25 12t-.057-.287t-.163-.243");
}

</style>
