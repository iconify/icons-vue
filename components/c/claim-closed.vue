<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjmc0i4ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:claim-closed" /></template>
<style>
.gjmc0i4ph {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 4.25Q2.25 4.25 2.25 7v10q0 2.75 2.75 2.75h14q2.75 0 2.75-2.75V9q0-2.75-2.75-2.75h-7.189L10.03 4.47q-.105-.106-.243-.163T9.5 4.25zm6.25 9.439l3.47-3.469q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-4 4q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-2.25-2.25q-.106-.105-.163-.243T8.25 12.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T9 11.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
