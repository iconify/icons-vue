<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f10aaibbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chess-bishop" /></template>
<style>
.f10aaibbj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.25 10.5q0-4.401-4.834-7.624q-.092-.062-.199-.094q-.106-.032-.217-.032t-.217.032t-.199.094Q6.75 6.099 6.75 10.5q0 3.252 2.318 4.424L7.959 18.25H6.75q-2 0-2 2t2 2h10.5q2 0 2-2t-2-2h-1.209l-1.109-3.326q2.318-1.172 2.318-4.424m-5.47-.22q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113l3.5-3.5q.105-.106.243-.163t.287-.057t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113zm2.679 7.97l-1-3h-2.918l-1 3z");
}

</style>
