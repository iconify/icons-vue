<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc16i11je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-right-circle" /></template>
<style>
.lc16i11je {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m15.28-.53l-4-4q-.105-.106-.243-.163T12.5 7.25t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T11.75 8t.014.146q.015.073.043.141t.069.13t.094.113l2.719 2.72H7.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6.75 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7.189l-2.719 2.72q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l4-4q.106-.105.163-.243T17.25 12t-.057-.287t-.163-.243");
}

</style>
