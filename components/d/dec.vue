<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGbdO2jCBO)" class="ex1g24byf"/><path fill="url(#SVGm1AuHRrQ)" class="a-j3pp8ta"/><path fill="url(#SVGJjt57NuA)" class="qmpykabcl"/><path class="fe89isb6g"/><defs><linearGradient id="SVGbdO2jCBO" x1="12.001" x2="12.001" y1="20.185" y2="3.326" gradientUnits="userSpaceOnUse"><stop class="ayk02cb2s"/><stop offset=".32" class="yojn3pbel"/><stop offset=".53" class="it6s-e23w"/><stop offset=".72" class="z8kf90v_i"/><stop offset=".88" class="ubqfcebhn"/><stop offset="1" class="qsvvj4xhw"/></linearGradient><linearGradient id="SVGm1AuHRrQ" x1="2.981" x2="21.239" y1="12.003" y2="12.003" gradientUnits="userSpaceOnUse"><stop class="r_pfrw6tp"/><stop offset="1" class="igpa--86j"/></linearGradient><linearGradient id="SVGJjt57NuA" x1="3" x2="21" y1="12.003" y2="12.003" gradientUnits="userSpaceOnUse"><stop class="qsvvj4xhw"/><stop offset=".28" class="r7yc-35dm"/><stop offset=".48" class="jng_az78l"/><stop offset=".64" class="ukx_tc7vk"/><stop offset=".79" class="ap9ude_jr"/><stop offset=".93" class="j3sw9fhhd"/><stop offset="1" class="tdzthxbxw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dec" /></template>
<style>
.a-j3pp8ta {
  d: path("M16.5 4.059L12 12.003l4.5 7.938l4.5-7.938z");
}

.ap9ude_jr {
  stop-color: var(--svg-color--3c6fce, #3c6fce);
}

.ayk02cb2s {
  stop-color: var(--svg-color--74c5ee, #74c5ee);
}

.ex1g24byf {
  d: path("M16.5 4.059h-9l4.5 7.944z");
}

.fe89isb6g {
  fill: var(--svg-color--74c5ee, #74c5ee);
  d: path("m12 12.002l-4.5 7.94h9z");
}

.ft5dv1b6b {
  fill: none;
}

.igpa--86j {
  stop-color: var(--svg-color--42c0c6, #42c0c6);
}

.it6s-e23w {
  stop-color: var(--svg-color--6eb9f1, #6eb9f1);
}

.j3sw9fhhd {
  stop-color: var(--svg-color--3166b3, #3166b3);
}

.jng_az78l {
  stop-color: var(--svg-color--4a7cf3, #4a7cf3);
}

.qmpykabcl {
  d: path("M7.5 4.059L3 12.003l4.5 7.938l4.5-7.938z");
}

.qsvvj4xhw {
  stop-color: var(--svg-color--4f80ff, #4f80ff);
}

.r_pfrw6tp {
  stop-color: var(--svg-color--96d4c8, #96d4c8);
}

.r7yc-35dm {
  stop-color: var(--svg-color--4e7ffc, #4e7ffc);
}

.tdzthxbxw {
  stop-color: var(--svg-color--2b60a3, #2b60a3);
}

.ubqfcebhn {
  stop-color: var(--svg-color--5a95fa, #5a95fa);
}

.ukx_tc7vk {
  stop-color: var(--svg-color--4477e4, #4477e4);
}

.yojn3pbel {
  stop-color: var(--svg-color--73c2ef, #73c2ef);
}

.z8kf90v_i {
  stop-color: var(--svg-color--66aaf5, #66aaf5);
}

</style>
