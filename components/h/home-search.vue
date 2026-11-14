<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="civpg7bas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-search" /></template>
<style>
.civpg7bas {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.596 9.416l6.75-5.956Q12 2 13.654 3.46l6.75 5.956q.846.746.846 1.874v7.46q0 2.5-2.5 2.5H5.25q-2.5 0-2.5-2.5v-7.46q0-1.128.846-1.874M11 10q-3.5 0-3.5 3.5T11 17q1.22 0 2.014-.425l1.706 1.705q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.705-1.706q.425-.794.425-2.014q0-3.5-3.5-3.5");
}

</style>
