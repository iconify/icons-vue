<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7s5u43ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bezier-tangent" /></template>
<style>
.m7s5u43ev {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.608 9.547l5.922 5.923q.106.105.163.243t.057.287t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-3.004-3.004q.034.355.034.724q0 2.796-1.977 4.773T9.75 21t-4.773-1.977T3 14.25t1.977-4.773T9.75 7.5q.369 0 .724.034L7.47 4.53q-.053-.052-.094-.113t-.069-.13t-.043-.141T7.25 4t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.105-.106.243-.163T8 3.25t.287.057t.243.163l5.933 5.932q.082.063.145.145");
}

</style>
