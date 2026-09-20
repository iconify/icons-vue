<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGsCmBKEug)" class="r4i437pya"/><path class="ymdcmsdhh"/></g><defs><linearGradient id="SVGsCmBKEug" x1="4.98" x2="19.065" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="xm2s_acyl"/><stop offset=".48" class="k96bt45ga"/><stop offset="1" class="ky09lxb2t"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gxa-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.k96bt45ga {
  stop-color: var(--svg-color--a472ff, #a472ff);
}

.ky09lxb2t {
  stop-color: var(--svg-color--543fff, #543fff);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xm2s_acyl {
  stop-color: var(--svg-color--13efcf, #13efcf);
}

.ymdcmsdhh {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 18a6.09 6.09 0 0 1-5.965-5H4c.545 3.95 4.005 7 8 7s7.455-3.05 8-7h-2.035A6.09 6.09 0 0 1 12 18m0-12a6.1 6.1 0 0 1 5.7 4h-2.21a4.01 4.01 0 0 0-3.515-1.985C9.86 8.055 8.005 9.865 8 12a4.095 4.095 0 0 0 3.975 4a4.02 4.02 0 0 0 3.93-3H12.25a1.97 1.97 0 0 1 0-2H20c-.545-3.95-4.005-7-8-7s-7.455 3.05-8 7h2.035c.5-2.86 3.06-5.015 5.965-5");
}

</style>
