<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4zd1nqhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cinema-camera-off" /></template>
<style>
.n4zd1nqhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.6 18.5H3V10h3.1m7.8 0H15v1.1M4.5 10q-.149-.224-.255-.471t-.167-.509t-.074-.53q-.014-.269.021-.536m6.012-1.881q.101-.088.21-.166t.225-.147q.116-.068.237-.126t.247-.105t.256-.082q.129-.035.262-.059q.132-.023.266-.035t.268-.011q.134 0 .268.012t.266.037t.262.06q.129.036.255.084q.126.047.247.106t.236.127q.115.069.224.148q.108.079.21.168t.194.186q.093.098.177.203t.158.219q.075.112.138.231t.117.243t.094.252q.042.129.072.26q.03.132.047.265q.018.134.024.269t0 .269q-.007.135-.025.269q-.018.133-.048.265q-.031.131-.073.259q-.042.129-.095.252q-.053.124-.117.243T14.5 10m1.501 2.045L20.5 10v6.558M3.5 3.5l17 17");
}

</style>
