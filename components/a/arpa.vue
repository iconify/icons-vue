<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="es4owbz5v"/><path fill="url(#SVGyI4LidcA)" class="p_s2j7xtr"/><path fill="url(#SVGRY4WfdNm)" class="rvac9pbeh"/><defs><linearGradient id="SVGyI4LidcA" x1="13.086" x2="13.451" y1="4.147" y2="19.425" gradientUnits="userSpaceOnUse"><stop class="vzi3mhxsc"/><stop offset="1" class="c7w1inv7w"/></linearGradient><linearGradient id="SVGRY4WfdNm" x1="12.157" x2="3.456" y1="4.125" y2="18.12" gradientUnits="userSpaceOnUse"><stop class="dswc79hmp"/><stop offset="1" class="nk5i8ti2e"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arpa" /></template>
<style>
.c7w1inv7w {
  stop-color: var(--svg-color--939493, #939493);
}

.dswc79hmp {
  stop-color: var(--svg-color--dcebf5, #dcebf5);
}

.es4owbz5v {
  fill: var(--svg-color--5a5967, #5a5967);
  d: path("M3.967 19.875L3 18.188h14.152L12 9.165l.95-1.67l7.054 12.38z");
}

.ft5dv1b6b {
  fill: none;
}

.nk5i8ti2e {
  stop-color: var(--svg-color--b9c6cc, #b9c6cc);
}

.p_s2j7xtr {
  d: path("M12.945 4.125L5.87 16.5H7.8l5.146-9l7.06 12.375L21 18.17z");
}

.rvac9pbeh {
  d: path("m3 18.187l8.078-14.062h1.873L5.863 16.5h10.328l.961 1.687z");
}

.vzi3mhxsc {
  stop-color: var(--svg-color--cbcccd, #cbcccd);
}

</style>
