<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1ojnp01h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-turn-down-left" /></template>
<style>
.p1ojnp01h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.5 5.75h8q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T21.25 5t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-8q-2.382 0-4.066 1.684T6.75 10v7.189L4.03 14.47q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.106.105-.163.243T2.75 15t.057.287t.163.243l4 4q.105.106.243.163t.287.057q.148 0 .285-.056t.242-.16l.003-.004l4-4q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094l-2.72 2.719V10q0-1.76 1.245-3.005T12.5 5.75");
}

</style>
