<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGeeMxpeTQ)" class="r4i437pya"/><path clip-rule="evenodd" class="g42pvac4v"/></g><defs><linearGradient id="SVGeeMxpeTQ" x1="12" x2="12" y1="4.259" y2="19.742" gradientUnits="userSpaceOnUse"><stop class="p_5nz4hjx"/><stop offset="1" class="de54ffb6m"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ant-background" /></template>
<style>
.de54ffb6m {
  stop-color: var(--svg-color--03ccfd, #03ccfd);
}

.ft5dv1b6b {
  fill: none;
}

.g42pvac4v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M8.54 5.572a5.8 5.8 0 0 1 2.301-.485l-.764-.78s3.076-.53 7.009 1.917c0 0 .056.125 0 .482c0 0 1.864.829 2.012 2.427c.16 1.6-.82 2.516-1.611 2.64c0 0 .41-.655-.224-1.011a.83.83 0 0 0-.457-.096c-1.211 0-1.351 1.416-1.351 1.416c.046 2.245 3.643 2.245 4.545 2.245c-.765 2.973-4.212 5.414-7.65 5.414c-3.2 0-8.35-2.29-8.35-7.823c0-1.762 1.399-4.982 4.54-6.346m7.39.97c-.196.202-.364.29-.41.318l-.019.01c-1.109-.25-1.51-.829-1.51-.829a5.1 5.1 0 0 1 2.684.675s-.372-.126-.745-.174");
}

.p_5nz4hjx {
  stop-color: var(--svg-color--02e8f7, #02e8f7);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
