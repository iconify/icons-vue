<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGTl1Zdboy)" class="r4i437pya"/><path class="lb4a-hfzu"/></g><defs><linearGradient id="SVGTl1Zdboy" x1="11.146" x2="11.217" y1="4" y2="19.742" gradientUnits="userSpaceOnUse"><stop class="xawtaybfq"/><stop offset=".54" class="l_3qguzbk"/><stop offset=".8" class="b65jfnp2o"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fcon-background" /></template>
<style>
.b65jfnp2o {
  stop-color: var(--svg-color--46f7b0, #46f7b0);
}

.ft5dv1b6b {
  fill: none;
}

.l_3qguzbk {
  stop-color: var(--svg-color--26baf8, #26baf8);
}

.lb4a-hfzu {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.223 5.947L12 4L9.777 5.947v5.86l1.196 1.12l.605-.65l-.912-.853V6.347L12 5.183l1.334 1.164v5.077L8.888 15.6v-4.93l-.756.755A.45.45 0 0 0 8 11.74v5.913l6.224-5.846zm1.645 5.482a.45.45 0 0 1 .133.311v5.9l-3.503-3.22l.605-.657l2.01 1.85v-4.944l.755.755zM12 14.848l-.444.413v4.33L12 20l.445-.409v-4.33l-.445-.41zM9.777 16.98l.89-.813v2.783l-.712-.654a.53.53 0 0 1-.178-.395zm4.446-.035l-.89-.872v2.935l.721-.658a.55.55 0 0 0 .169-.4z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xawtaybfq {
  stop-color: var(--svg-color--6167fb, #6167fb);
}

</style>
