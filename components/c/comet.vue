<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csir65biq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:comet" /></template>
<style>
.csir65biq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.241 16.699q-.075-1.19-.748-2.131L20.53 4.53q.106-.105.163-.243T20.75 4t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043T20 3.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094L9.432 13.507q-.941-.673-2.131-.748L12.03 8.03q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163T11.5 6.75t-.287.057t-.243.163l-7 7q-.09.089-.145.204Q2.75 15.364 2.75 17q0 1.76 1.245 3.005T7 21.25q1.636 0 2.826-1.075q.115-.055.204-.145l7-7q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094z");
}

</style>
