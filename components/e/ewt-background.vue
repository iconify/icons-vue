<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="bhoypoe5y"/><path class="fyun8rbpq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ewt-background" /></template>
<style>
.bhoypoe5y {
  fill: var(--svg-color--a25cf8, #a25cf8);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.fyun8rbpq {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.354 7.58a9 9 0 0 0-.623-1.233c-.207-.334-.447-.653-.709-.871a.1.1 0 0 0-.098-.014l-.946.41a.098.098 0 0 0-.035.153c.188.22.628.743.776.982c.184.297.368.663.532 1.057c1.18 2.838.681 9.419-3.367 9.248c-.935-.04-1.716-.509-2.34-1.247c-.632-.745-1.083-1.746-1.324-2.764c-.244-1.023-.26-1.999-.086-2.684c.087-.34.211-.57.34-.706a.54.54 0 0 1 .422-.185c.412 0 .667.156.847.394c.2.264.339.679.382 1.222c.087 1.07-.277 2.62-.793 3.568a.1.1 0 0 0 .007.106l.634.86a.1.1 0 0 0 .084.039a.1.1 0 0 0 .078-.05c.625-1.174 1.29-3.321 1.186-4.625c-.055-.678-.237-1.354-.63-1.874c-.413-.546-1.021-.87-1.795-.87c-.515 0-.952.208-1.283.558c-.318.336-.52.782-.64 1.252c-.239.938-.193 2.13.081 3.287c.277 1.163.801 2.354 1.584 3.279c.789.932 1.86 1.613 3.196 1.67c5.05.213 6.025-7.342 4.52-10.961m-13.66 9.048C4.61 15.076 4.145 13.273 4 11.82a.1.1 0 0 1 .06-.099l1.003-.408a.1.1 0 0 1 .119.038a.1.1 0 0 1 .014.042c.144 1.376.58 3.258 1.475 4.54c.454.65 1.001 1.11 1.654 1.305c.634.19 1.526.063 2.59-.42a.1.1 0 0 1 .117.027l.725.914a.096.096 0 0 1-.035.147c-1.175.638-2.772.775-3.736.488c-.986-.295-1.734-.968-2.292-1.767");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
