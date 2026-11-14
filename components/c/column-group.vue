<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ls2to96st"/><path class="sa-r0267g"/><path class="xikv_u7kv"/><path class="h__c-4bpv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:column-group" /></template>
<style>
.h__c-4bpv {
  d: path("M13.5 13.5V20a1.5 1.5 0 0 0 1.5 1.5h4a1.5 1.5 0 0 0 1.5-1.5v-6.5M3.5 17h7m3 0h7m-17-9V6h6m5 0h6v2m-11-4.5h5v5h-5ZM10.75 6h2.5");
}

.ls2to96st {
  fill: currentColor;
  d: path("M3.5 13.5V12A1.5 1.5 0 0 1 5 10.5h4a1.5 1.5 0 0 1 1.5 1.5v1.5Z");
}

.sa-r0267g {
  d: path("M3.5 13.5V20A1.5 1.5 0 0 0 5 21.5h4a1.5 1.5 0 0 0 1.5-1.5v-6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xikv_u7kv {
  fill: currentColor;
  d: path("M13.5 13.5V12a1.5 1.5 0 0 1 1.5-1.5h4a1.5 1.5 0 0 1 1.5 1.5v1.5Z");
}

</style>
