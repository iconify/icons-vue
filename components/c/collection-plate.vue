<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jcn_3_4ex"/><path class="kvx5d4niy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:collection-plate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jcn_3_4ex {
  d: path("M19.4 11.5h2.1C20.5 15.25 17 17 12 17s-8.5-1.75-9.5-5.5h6.1m.4 8.25h6M9.242 5.01q-.151.012-.301.038q-.149.026-.295.066t-.288.093q-.142.054-.278.12t-.266.145t-.252.169q-.121.09-.234.191t-.216.213q-.102.111-.194.232q-.092.12-.173.249q-.08.128-.148.264q-.069.135-.124.276t-.097.287t-.07.295t-.042.3t-.014.302q0 .13.01.259q.011.13.031.258q.021.129.052.255t.072.249q.041.124.091.244q.051.119.111.235t.129.225t.146.214q.078.105.163.202t.179.189q.093.09.193.173t.207.158q.106.074.218.14t.229.123t.238.104t.246.085");
}

.kvx5d4niy {
  d: path("M10.75 8.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
