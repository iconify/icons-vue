<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7mAieb1x)" class="r4i437pya"/><path clip-rule="evenodd" class="mlgyh0red"/></g><defs><linearGradient id="SVG7mAieb1x" x1="20.52" x2="4.492" y1="11.998" y2="11.998" gradientUnits="userSpaceOnUse"><stop class="dkzpq1bkh"/><stop offset="1" class="ymshwgb8g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ern-background" /></template>
<style>
.dkzpq1bkh {
  stop-color: var(--svg-color--23addd, #23addd);
}

.ft5dv1b6b {
  fill: none;
}

.mlgyh0red {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m11.936 13.826l.864.752c.932.88 1.888 1.472 3.296 1.42a3.96 3.96 0 0 0 3.904-4c0-2.2-1.748-4-3.904-4c-.944 0-1.852.228-2.532.84l-.98.96l.52.524l.896-.88c.552-.496 1.24-.644 2-.644c1.74 0 3.2 1.428 3.2 3.2s-1.416 3.2-3.156 3.2c-1.136.04-1.88-.448-2.636-1.16l-.86-.884l.58-.6v.005l1.68-1.688a1.64 1.64 0 0 1 2.292 2.335c-.636.644-1.696.44-2.22-.136l-.66-.616l-.588.616l.652.664c.872.84 2.52.94 3.44 0a2.44 2.44 0 0 0-.032-3.4a2.504 2.504 0 0 0-3.524-.011l-3.62 3.667c-.752.712-1.456 1.252-2.592 1.208a3.16 3.16 0 0 1-3.156-3.18a3.19 3.19 0 0 1 3.156-3.22c.76 0 1.492.192 2.04.688l1.456 1.416l-1.836 1.816l-.492.504a1.62 1.62 0 0 1-1.948.28l1.368-1.392l1.4-1.455l-.312-.32a2.28 2.28 0 0 0-3.336 0a2.436 2.436 0 0 0 0 3.4a2.33 2.33 0 0 0 3.336 0l2.848-2.845l-.5-.504l-1.544-1.504c-.68-.616-1.588-.84-2.532-.84A3.94 3.94 0 0 0 4 12.014c0 2.196 1.748 3.976 3.904 3.976c1.408.052 2.332-.536 3.264-1.416l.768-.752zM6.844 10.87c-.556.569-.56 1.312-.148 1.96l2.052-2.12c-.692-.46-1.348-.408-1.904.16");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ymshwgb8g {
  stop-color: var(--svg-color--28a6e1, #28a6e1);
}

</style>
