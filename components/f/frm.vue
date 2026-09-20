<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGbJ3x1aGb)" class="n8288bccj"/><path fill="url(#SVGbHjaRdJz)" class="dbjf8obuw"/><path class="wa4ghpbrr"/><path class="emp6nib9g"/><defs><linearGradient id="SVGbJ3x1aGb" x1="3.537" x2="18.864" y1="16.055" y2="7.509" gradientUnits="userSpaceOnUse"><stop offset=".05" class="c71na2wpg"/><stop offset=".3" class="y-kkxsbkb"/><stop offset=".9" class="k9-9dgqdr"/></linearGradient><linearGradient id="SVGbHjaRdJz" x1="2.029" x2="25.758" y1="18.379" y2="10.902" gradientUnits="userSpaceOnUse"><stop offset=".2" class="y6unhbaco"/><stop offset=".62" class="ep3vtxwcp"/><stop offset=".92" class="d7pw99b0o"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:frm" /></template>
<style>
.c71na2wpg {
  stop-color: var(--svg-color--c5c3c5, #c5c3c5);
}

.d7pw99b0o {
  stop-color: var(--svg-color--cca362, #cca362);
}

.dbjf8obuw {
  d: path("m16.5 8.198l-9 5.082v2.41l9-5.348z");
}

.emp6nib9g {
  fill: var(--svg-color--cca362, #cca362);
  d: path("m18.882 7.13l.794.508v8.587L11.63 21l-1.588-1.07l8.047-4.775V7.66l.794-.535z");
}

.ep3vtxwcp {
  stop-color: var(--svg-color--ecc77c, #ecc77c);
}

.ft5dv1b6b {
  fill: none;
}

.k9-9dgqdr {
  stop-color: var(--svg-color--bebbbe, #bebbbe);
}

.n8288bccj {
  d: path("m4.323 16.24l.794.461l.794-.466v-3.44L17.76 6.202l-1.588-1.07l-10.26 5.522V8.432l8.671-4.363L12.995 3L4.323 7.394z");
}

.wa4ghpbrr {
  fill: var(--svg-color--cca362, #cca362);
  d: path("m8.56 18.899l-1.589-1.07l9.53-5.882v2.145l-7.942 4.817z");
}

.y-kkxsbkb {
  stop-color: var(--svg-color--f2f2f2, #f2f2f2);
}

.y6unhbaco {
  stop-color: var(--svg-color--caa467, #caa467);
}

</style>
