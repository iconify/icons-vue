<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hgzzxdb5e"/><path class="oov2r6b0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposition" /></template>
<style>
.hgzzxdb5e {
  d: path("M12.2 12H7.5V2.5h5v8.7");
}

.oov2r6b0r {
  d: path("M4.75 9.5q0 .129.006.258q.007.128.019.257q.013.128.032.255q.019.128.044.254q.025.127.056.252q.032.125.069.248t.081.245q.043.121.093.24q.049.119.104.236t.116.23t.127.224t.138.218q.071.107.148.21q.077.104.159.204q.081.099.168.195q.087.095.178.186t.186.178q.096.087.195.168q.1.082.204.159t.21.148q.107.072.218.138t.224.127t.23.116t.236.104q.119.05.24.093q.122.044.245.081t.248.069q.125.031.252.056q.126.025.254.044q.127.019.255.032q.129.012.257.019q.129.006.258.006q.563 0 1.114-.119q.55-.12 1.063-.354m2.789-3.073q.284-.829.284-1.704M10 14.75v5.75m-2.5 0h4.7M15 14h6.75v8H15Zm2.5 2.75h1.75m-1.75 2.5h1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
