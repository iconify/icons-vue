<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xni3aacdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bowling-finger-holes" /></template>
<style>
.xni3aacdc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.888 7.888Q2.25 13.526 2.25 21.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-7.352 5.199-12.551T21.5 3.75q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 3t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-7.974 0-13.612 5.638M17.5 6.75q-2.75 0-2.75 2.75t2.75 2.75t2.75-2.75t-2.75-2.75M9.25 13.5q0-2.75 2.75-2.75t2.75 2.75T12 16.25T9.25 13.5m5.5 4.5q0-2.75 2.75-2.75T20.25 18t-2.75 2.75T14.75 18");
}

</style>
