<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0un7rbgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ad-block" /></template>
<style>
.g0un7rbgy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.964 5.097L21.03 4.03q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-1.458 1.458q-.657-.178-1.387-.178H6.875q-2.123 0-3.624 1.501T1.75 9.375v5.25q0 2.123 1.501 3.624q.374.373.785.654L2.97 19.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l1.458-1.458q.657.178 1.387.178h10.25q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624q-.374-.373-.785-.654M6.5 6.75h1.75q2.25 0 2.25 2.25t-2.25 2.25H6.5q-2.25 0-2.25-2.25T6.5 6.75");
}

</style>
