<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="kw88xoflj"/><path class="gm4wltbtz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gamefi-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gm4wltbtz {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 5.787L5.77 4L8.8 7.061l.01-.005l1.766 1.787v.01L8.811 10.64l-.011-.005l-3.03 3.061L4 11.909l3.035-3.061zm16 6.304l-1.77-1.787l-3.03 3.061l-.01-.005l-1.766 1.787v.01l1.765 1.787l.011-.005L18.23 20L20 18.213l-3.035-3.061zm-6.4 6.122L11.84 20L8.8 16.939L5.77 20L4 18.213l3.035-3.061l-.011-.005L8.8 13.36l.005.005l.011-.005l1.765 1.787v.005zM18.043 4l1.77 1.787l-3.029 3.061l.005.005l-1.77 1.787l-.006-.005l-.01.005l-1.766-1.787l.006-.005l-3.035-3.061L11.973 4l3.035 3.061L18.038 4z");
}

.kw88xoflj {
  fill: var(--svg-color--b9fb01, #b9fb01);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
