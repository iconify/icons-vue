<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="geee2eb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:force" /></template>
<style>
.geee2eb2h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 5.25h2q1.76 0 3.005 1.245T22.25 9.5v5q0 1.76-1.245 3.005T18 18.75h-2q-1.76 0-3.005-1.245T11.75 14.5v-5q0-1.76 1.245-3.005T16 5.25m-5.72 6.219l-3-2.999q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243T6 9t.057.287t.163.243l1.719 1.72H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5.439L6.22 14.47q-.106.105-.163.243T6 15t.057.287t.163.243q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l3-2.999v-.001q.106-.105.163-.243T10.5 12t-.057-.287t-.163-.243z");
}

</style>
