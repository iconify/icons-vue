<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="agvvb3bjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:machete" /></template>
<style>
.agvvb3bjw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.75 12.189l9.22-9.219q1.499-1.5 2.847-.945q1.425.587 1.178 2.808q-.01.097-.046.189Q19.741 10.7 12.19 15.63l.09.09q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T11.75 17t-.287-.057t-.243-.163l-.295-.294q-.166.29-.42.544L8.03 19.505q-.732.733-1.768.733q-1.035 0-1.767-.733q-.733-.732-.733-1.768q0-1.035.733-1.767l2.475-2.475q.254-.254.544-.42l-.294-.295q-.106-.105-.163-.243T7 12.25t.057-.287t.163-.243q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
