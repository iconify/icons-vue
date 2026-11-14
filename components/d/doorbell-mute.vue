<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aftzd8euq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:doorbell-mute" /></template>
<style>
.aftzd8euq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.75 14.922L7.178 4.349q.322-.481.756-.915Q9.618 1.75 12 1.75t4.066 1.684T17.75 7.5zM4.03 2.97l17 17q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-17-17q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.75 3.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m12.036 17.596q.434-.434.756-.915l-2.745-2.746q-.741.595-2.077.595q-3 0-3-3q0-1.336.595-2.077L6.25 9.078V16.5q0 2.382 1.684 4.066T12 22.25t4.066-1.684");
}

</style>
