<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGM43sScEY)" class="s7-cb0eqm"/><defs><linearGradient id="SVGM43sScEY" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="ixn5c2bso"/><stop offset="1" class="yuo4ptbrl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ktc" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ixn5c2bso {
  stop-color: var(--svg-color--53f3ff, #53f3ff);
}

.s7-cb0eqm {
  d: path("M3.321 3v2.571h2.572V3zm0 18V6.857h2.572v7.38L17.078 3h3.6zm8.036-5.722A776 776 0 0 1 17.078 21h3.6l-7.43-7.714z");
}

.yuo4ptbrl {
  stop-color: var(--svg-color--38cdee, #38cdee);
}

</style>
