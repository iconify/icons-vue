<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tv813pb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bookmark-check" /></template>
<style>
.tv813pb-m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.375 2.25h-6.75q-1.398 0-2.386.989q-.989.988-.989 2.386V17.25q0 1.622 1.451 2.348t2.749-.248l1.425-1.069q1.125-.844 2.25 0l1.425 1.069q1.298.973 2.749.248q1.451-.726 1.451-2.348V5.625q0-1.398-.989-2.386q-.988-.989-2.386-.989M11 10.439l3.47-3.469q.105-.106.243-.163T15 6.75t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-4 4q-.105.106-.243.163T11 12.25t-.287-.057t-.243-.163l-2-2q-.106-.105-.163-.243T8.25 9.5t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043T9 8.75t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
