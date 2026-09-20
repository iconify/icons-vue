<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGjR1lldgC)" class="r4i437pya"/><path class="btf3nyb_s"/></g><defs><linearGradient id="SVGjR1lldgC" x1="8.229" x2="18.941" y1="6.286" y2="15.307" gradientUnits="userSpaceOnUse"><stop class="myp3dzior"/><stop offset=".45" class="yd3abrb8c"/><stop offset="1" class="lb42xlbia"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:del-background" /></template>
<style>
.btf3nyb_s {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.4 4H5.6v3.2h9.067v9.6H5.6V20h12.8zm-6.933 6.4H5.6v3.2h5.867z");
}

.ft5dv1b6b {
  fill: none;
}

.lb42xlbia {
  stop-color: var(--svg-color--9845f5, #9845f5);
}

.myp3dzior {
  stop-color: var(--svg-color--02fdad, #02fdad);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.yd3abrb8c {
  stop-color: var(--svg-color--457df4, #457df4);
}

</style>
