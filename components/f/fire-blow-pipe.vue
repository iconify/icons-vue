<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l23jc2fgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-blow-pipe" /></template>
<style>
.l23jc2fgs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.53 1.97q3.22 3.219 3.22 6.53q0 3.75-3.75 3.75T14.25 8.5q0-3.311 3.22-6.53q.052-.053.113-.094t.13-.069t.141-.043T18 1.75t.146.014q.073.015.141.043t.13.069q.061.041.113.094m-14.56 15l6-6q.633-.634 1.53-.634t1.53.634t.634 1.53q0 .897-.634 1.53l-6 6q-.249.25-.539.401l.289.289q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163T6.25 22t-.287-.057t-.243-.163l-1.75-1.75h-.001L2.22 18.28q-.053-.052-.094-.113t-.069-.13t-.043-.141T2 17.75t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163T2.75 17t.287.057t.243.163l.289.289q.151-.29.401-.539");
}

</style>
