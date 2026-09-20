<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="jmaqydbtg"/><path class="oprd--b1j"/><path class="stvpgfb9u"/><path class="gua_2kbit"/><path class="tm8wtyb9h"/><path class="x4vaqci_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:extra" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gua_2kbit {
  fill: var(--svg-color--146ae5, #146ae5);
  d: path("M11.513 8.295v1.291H8.982a1.005 1.005 0 0 0-1.006 1.017c0 .556.455.868 1.006.868h1.959v1.324H8.982a2.21 2.21 0 0 1-2.276-2.208a2.283 2.283 0 0 1 2.276-2.292zm1.847 7.94l3.934-5.293h-1.398L12 16.236z");
}

.jmaqydbtg {
  fill: var(--svg-color--b0d1fa, #b0d1fa);
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-1.059a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883");
}

.oprd--b1j {
  fill: var(--svg-color--146ae5, #146ae5);
  d: path("M11.513 16.235v-1.292h-2.53a1.004 1.004 0 0 1-1.007-1.016c0-.556.455-1.133 1.006-1.133h1.959v-1.15H8.982a2.28 2.28 0 0 0-2.276 2.299a2.283 2.283 0 0 0 2.276 2.292z");
}

.stvpgfb9u {
  fill: var(--svg-color--194989, #194989);
  d: path("M7.184 12.53c.37.223.953.424 1.604.297c.577-.117.063-.583-.62-1.027c-.389.148-.73.401-.984.73");
}

.tm8wtyb9h {
  fill: var(--svg-color--1d4988, #1d4988);
  d: path("m13.82 13.757l.662.964l.62-.832l-.747-.852l-.53.72z");
}

.x4vaqci_x {
  fill: var(--svg-color--146ae5, #146ae5);
  d: path("M15.934 16.236L12 10.942h1.398l3.896 5.294z");
}

</style>
