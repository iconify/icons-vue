<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9u0p2box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-turn-down-right" /></template>
<style>
.y9u0p2box {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 4.25h-8q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q2.75 4.926 2.75 5t.014.146t.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h8q1.76 0 3.005 1.245T15.75 10v7.189l-2.72-2.719q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l4 4q.105.106.243.163t.287.057t.287-.057t.243-.163l4-4q.106-.105.163-.243T21.25 15t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-2.72 2.719V10q0-2.382-1.684-4.066T11.5 4.25");
}

</style>
