<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgaqcqbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:heart-check" /></template>
<style>
.wgaqcqbrw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.989 17.08q2.305 2.146 4.62 3.56q.088.054.188.082q.099.028.203.028t.203-.028t.188-.082q2.315-1.414 4.62-3.56q4.739-4.41 4.739-8.33q0-2.298-1.601-3.899T16.25 3.25q-2.621 0-4.25 1.953Q10.371 3.25 7.75 3.25q-2.298 0-3.899 1.601T2.25 8.75q0 3.92 4.739 8.33M11 11.939l3.47-3.469q.105-.106.243-.163T15 8.25t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-4 4q-.105.106-.243.163T11 13.75t-.287-.057t-.243-.163l-2-2q-.106-.105-.163-.243T8.25 11t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T9 10.25t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
