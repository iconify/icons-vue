<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="z9wgrzaeb"/><path class="qm20hhbbb"/><path class="lmef1bcjx"/><path class="znj36yb0v"/><path clip-rule="evenodd" class="e52-bn-qz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ejs-background" /></template>
<style>
.e52-bn-qz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.556a7.556 7.556 0 1 0 0-15.112a7.556 7.556 0 0 0 0 15.112M12 20a7.999 7.999 0 1 0 0-15.998A7.999 7.999 0 0 0 12 20");
}

.ft5dv1b6b {
  fill: none;
}

.lmef1bcjx {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.334 14.586l2.462-2.457a.623.623 0 1 1-.885-.88l-2.08 2.075c.116.436.28.862.503 1.262m4.533-.377l-2.453 2.457a5.5 5.5 0 0 0 1.262.503l2.155-2.16l-.08.08a.624.624 0 1 1-.884-.88");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qm20hhbbb {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.613 8.383L11.715 9.45l.378.382l-2.298 2.298a.623.623 0 1 1-.884-.88l4.413-4.414a5.333 5.333 0 1 0 3.84 3.84L12.75 15.09a.624.624 0 0 1-.88-.885l2.297-2.298l.418.414z");
}

.z9wgrzaeb {
  fill: var(--svg-color--ea3d72, #ea3d72);
  d: path("M24 0H0v24h24z");
}

.znj36yb0v {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.156 13.92l-2.742 2.746l.27.138l2.019-2.017a.62.62 0 0 1 .168-.578zm-5.231-.276l1.822-1.813a.63.63 0 0 1 .164-.582l-2.08 2.075l.094.325z");
}

</style>
