<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="poaj2qbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kitchen-range" /></template>
<style>
.poaj2qbes {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 2.75h9q1.76 0 3.005 1.245T20.75 7v2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 8.75H4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146V7q0-1.76 1.245-3.005T7.5 2.75M3.25 9.5q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h16q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V17q0 1.76-1.245 3.005T16.5 21.25h-9q-1.76 0-3.005-1.245T3.25 17zm3.5-3q0 1.75 1.75 1.75t1.75-1.75T8.5 4.75T6.75 6.5m8.75-1.75q-1.75 0-1.75 1.75t1.75 1.75t1.75-1.75t-1.75-1.75m-6.25 7q-2.5 0-2.5 2.5v1.5q0 2.5 2.5 2.5h5.5q2.5 0 2.5-2.5v-1.5q0-2.5-2.5-2.5z");
}

</style>
