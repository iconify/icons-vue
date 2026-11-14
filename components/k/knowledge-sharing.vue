<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sz3l8ebax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:knowledge-sharing" /></template>
<style>
.sz3l8ebax {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 1.75H7q-2.175 0-3.712 1.538Q1.75 4.825 1.75 7v5.5l.001.041q.176 3.227 2.999 4.469V21q0 .128.042.248q.043.121.122.221q.046.057.103.105t.121.083q.065.036.135.058t.144.03t.147.002q.074-.006.145-.027t.136-.054q.066-.034.124-.08l4.794-3.836H17q2.175 0 3.712-1.538q1.538-1.537 1.538-3.712V7q0-2.175-1.538-3.712Q19.175 1.75 17 1.75M9.75 13.5v-.593q-2-1.401-2-3.907q0-1.76 1.245-3.005T12 4.75t3.005 1.245T16.25 9q0 2.506-2 3.907v.593q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146");
}

</style>
