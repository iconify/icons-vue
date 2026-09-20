<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kf1ye04uk"/><path class="lr4sa460b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hifi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kf1ye04uk {
  fill: var(--svg-color--6e2ef4, #6e2ef4);
  d: path("M24 0H0v24h24z");
}

.lr4sa460b {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.535 12.263a1.816 1.816 0 0 1 0-2.569l5.162-5.162a1.817 1.817 0 0 1 2.57 2.57l-5.158 5.161a1.817 1.817 0 0 1-2.57 0zm5.472 1.732a1.815 1.815 0 0 1 0-2.57l1.422-1.42a1.817 1.817 0 1 1 2.569 2.569l-1.421 1.421a1.81 1.81 0 0 1-1.98.394a1.8 1.8 0 0 1-.59-.394m1.732 5.473a1.817 1.817 0 0 1 0-2.57l5.157-5.162a1.82 1.82 0 0 1 2.57 0a1.817 1.817 0 0 1 0 2.57l-5.158 5.162a1.82 1.82 0 0 1-2.569 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
