<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG6WNJNcPe)" class="hmt31wfuj"><path class="m0doiybxn"/><path class="klc72c_vv"/><path class="x3tfu1bzf"/><path class="s9w2_mx0q"/><path class="srwzlgh0u"/><path class="vm2238awy"/><path class="mz2jmobki"/><path class="ootszsbnl"/><path class="s-a-y9bxn"/></g><defs><clipPath id="SVG6WNJNcPe"><rect class="fng6irbns"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:baseball-broken" /></template>
<style>
.fng6irbns {
  width: 24px;
  height: 24px;
  fill: var(--svg-color--fff, #fff);
}

.ft5dv1b6b {
  fill: none;
}

.hmt31wfuj {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klc72c_vv {
  d: path("M5.19336 4.6743C7.69016 6.2738 9.20036 9.0348 9.20036 12C9.20036 14.9652 7.69016 17.7262 5.19336 19.3257");
}

.m0doiybxn {
  d: path("M12.0011 1.99832C13.7003 1.99696 15.4227 2.42905 17.0001 3.33975C21.783 6.10115 23.4218 12.2171 20.6604 17C17.899 21.7829 11.783 23.4217 7.0001 20.6603C2.21721 17.8989 0.578444 11.7829 3.33984 7.00001C4.25054 5.42263 5.52615 4.18722 6.99841 3.33878");
}

.mz2jmobki {
  d: path("M15.9504 12H13.6504");
}

.ootszsbnl {
  d: path("M7.03906 15.775L9.03096 16.925");
}

.s-a-y9bxn {
  d: path("M16.9606 15.775L14.9688 16.925");
}

.s9w2_mx0q {
  d: path("M7.03906 8.225L9.03096 7.075");
}

.srwzlgh0u {
  d: path("M16.9606 8.225L14.9688 7.075");
}

.vm2238awy {
  d: path("M8.05078 12H10.3508");
}

.x3tfu1bzf {
  d: path("M18.8078 19.3257C16.311 17.7262 14.8008 14.9652 14.8008 12C14.8008 9.0348 16.311 6.2738 18.8078 4.6743");
}

</style>
