<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ddqp2ac_b"/><path class="v-m_eob3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dept-produce-sign" /></template>
<style>
.ddqp2ac_b {
  d: path("M3 9.5h18V21H3Zm4-7v7m10-7v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v-m_eob3e {
  d: path("M9 18.25c0-4.25 2.5-6 6-6c0 3.75-2.5 6-6 6Zm0 0l3.5-3.5");
}

</style>
