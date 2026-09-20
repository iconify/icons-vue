<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGr2yHJqjb)" class="r4i437pya"/><path clip-rule="evenodd" class="s9j0fnwzk"/></g><defs><linearGradient id="SVGr2yHJqjb" x1="12" x2="12" y1="4.941" y2="19.059" gradientUnits="userSpaceOnUse"><stop class="s66acdchf"/><stop offset="1" class="k6sn7g4yt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aqtis-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k6sn7g4yt {
  stop-color: var(--svg-color--5ad9e6, #5ad9e6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s66acdchf {
  stop-color: var(--svg-color--bddc78, #bddc78);
}

.s9j0fnwzk {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.118 4.941L20 19.06H4zm-.504 1.784l3.398 4.324l-2.9-5.19zm2.447 3.844l-2.687-3.42l-.263.456l2.945 2.964zm-3.186-2.56l-.06.109l1.27 1.106zm2.683 3.092l-2.97-2.588l-.226.405l3.2 2.183zm-4.273-.32l-4.504 7.83h2.165zm-1.864 7.83h1.313l.805-7.105zm2.494-6.395l.15 5.553l-.846.593zm1.727 6.396h7.59l-.648-1.158zm6.711-1.577l-.659-1.186l-6.438 2.367zm-6.668.546l5.788-2.127l-.447-.8zm5.124-3.317l-.268-.48l-4.117 2.88zm-6.296 3.195l.584-.405l-.716-4.565zm-.15-7.99l1.148 7.293l4.706-3.294z");
}

</style>
