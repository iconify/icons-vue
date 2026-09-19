<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="nxdaeub3k"/><path class="jxvwb8lvj"/><circle class="jhpb5hbab"/><path class="wxpredccn"/><path class="dcdj05qvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:birdipedia" /></template>
<style>
.dcdj05qvx {
  d: path("m23.366 42.372l-1.035-7.36l-3.738-5.693l-.977-5.347l-.23-2.76l12.788-1.557");
}

.jhpb5hbab {
  cx: 25.436px;
  cy: 16.496px;
  r: 0.978px;
}

.jxvwb8lvj {
  d: path("m17.616 24.087l2.875-.575l2.012 1.207");
}

.nxdaeub3k {
  d: path("m5.622 34.734l6.343-7.481l-.407-5.245l1.22-7.034l-.407-5.164L7.493 5.5l11.954 1.87l6.424 2.765l5.001 6.953l-.487-.244l11.994 7.278l-.081.04l-9.027-1.341l-5.977-.814l-4.635 2.643l2.684 7.685l2.195 7.481l-1.138 2.4l-2.155.243l-4.066.04l-4.676-.934l-3.212-1.342l-2.561-1.667l-2.359-1.911z");
}

.wxpredccn {
  d: path("m29.896 16.275l-9.27-2.887l-7.32 1.87l12.361 2.806zm-.148.394l.69 3.048l-3.928 2.72m-13.548-7.091l1.146 16.273l4.14 6.958l.69 3.45");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
