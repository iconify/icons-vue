<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":197};
const content = `<path class="oa3cvddyb"/><path class="kvip2sb3j"/><path class="amgw9lbuf"/><path class="mvm6wbbmm"/><path class="s4gx1ho9w"/><path class="x4_884bsf"/><path class="gx2p5_ocn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-fonts-icon" /></template>
<style>
.amgw9lbuf {
  fill: var(--svg-color--34a853, #34a853);
  d: path("M256 140.8c0 30.635-24.832 55.467-55.467 55.467V85.333c30.635 0 55.467 24.832 55.467 55.467");
}

.gx2p5_ocn {
  fill: var(--svg-color--ea4335, #ea4335);
  d: path("M4.267 38.4C4.267 17.195 21.46 0 42.667 0c21.205 0 38.4 17.195 38.4 38.4s-17.195 38.4-38.4 38.4c-21.206 0-38.4-17.195-38.4-38.4");
}

.kvip2sb3j {
  fill: var(--svg-color--1a73e8, #1a73e8);
  d: path("M200.533 196.267h-76.8V0h76.8z");
}

.mvm6wbbmm {
  fill: var(--svg-color--0d652d, #0d652d);
  d: path("M200.533 196.267c-30.634 0-55.466-24.832-55.466-55.467s24.832-55.467 55.466-55.467z");
}

.oa3cvddyb {
  fill: var(--svg-color--fbbc04, #fbbc04);
  d: path("M0 196.267L123.733 0h76.8v27.307L93.867 196.267");
}

.s4gx1ho9w {
  fill: var(--svg-color--1a73e8, #1a73e8);
  d: path("M243.2 42.667c0 23.56-19.098 42.666-42.667 42.666V0c23.57 0 42.667 19.106 42.667 42.667");
}

.x4_884bsf {
  fill: var(--svg-color--174ea6, #174ea6);
  d: path("M200.533 85.333c-23.569 0-42.666-19.106-42.666-42.666S176.964 0 200.533 0z");
}

</style>
