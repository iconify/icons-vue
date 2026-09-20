<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tqk7a_b9x"/><path class="bq9q2xa2w"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hnt-background" /></template>
<style>
.bq9q2xa2w {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.839 4.885a3 3 0 0 0-.827 1.543A5.9 5.9 0 0 0 7.779 7.77a5.9 5.9 0 0 0-1.34 6.239a3.024 3.024 0 1 0 3.555 3.543a5.9 5.9 0 0 0 6.217-1.35a5.9 5.9 0 0 0 1.35-6.21a3.026 3.026 0 0 0 1.158-5.438a3.024 3.024 0 0 0-3.88.332m3.533.709a2 2 0 0 1-1.697 3.39a.3.3 0 0 0-.088 0a1.026 1.026 0 0 0-1.065 1.451a3.84 3.84 0 0 1-.768 4.31a3.84 3.84 0 0 1-4.31.767a1.025 1.025 0 0 0-1.298.376c-.12.187-.177.409-.16.631a.4.4 0 0 0 0 .102a2 2 0 0 1-.559 1.741a2 2 0 0 1-3.258-.647a2 2 0 0 1-.15-.765c0-.533.207-1.035.584-1.412a2.01 2.01 0 0 1 1.728-.564q.1.022.203.023a1.025 1.025 0 0 0 .961-.664c.095-.25.094-.537-.027-.798a3.84 3.84 0 0 1 .767-4.31a3.84 3.84 0 0 1 4.31-.767a1.02 1.02 0 0 0 1.13-.177a1.03 1.03 0 0 0 .314-.946a2 2 0 0 1 .558-1.741a2 2 0 0 1 2.825 0m-7.928 4.841a2.213 2.213 0 1 0 3.13 3.129a2.213 2.213 0 0 0-3.13-3.129");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tqk7a_b9x {
  fill: var(--svg-color--4655f6, #4655f6);
  d: path("M24 0H0v24h24z");
}

</style>
