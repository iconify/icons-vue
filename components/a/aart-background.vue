<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGq8pPrcKO)" class="r4i437pya"/><path class="s-t63rrjo"/><path class="rkkueqbux"/></g><defs><linearGradient id="SVGq8pPrcKO" x1="7.571" x2="14.454" y1="5.786" y2="18.805" gradientUnits="userSpaceOnUse"><stop class="s6k9lqbcf"/><stop offset=".19" class="jqobbj6lr"/><stop offset=".45" class="a_vge2bdv"/><stop offset=".69" class="iccw4bcpx"/><stop offset=".79" class="mkx4gzb-k"/><stop offset=".9" class="bvlvo7u-q"/><stop offset="1" class="lh5wz7bqm"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aart-background" /></template>
<style>
.a_vge2bdv {
  stop-color: var(--svg-color--67bbce, #67bbce);
}

.bvlvo7u-q {
  stop-color: var(--svg-color--e08c94, #e08c94);
}

.ft5dv1b6b {
  fill: none;
}

.iccw4bcpx {
  stop-color: var(--svg-color--382f4a, #382f4a);
}

.jqobbj6lr {
  stop-color: var(--svg-color--3b578e, #3b578e);
}

.lh5wz7bqm {
  stop-color: var(--svg-color--ce7782, #ce7782);
}

.mkx4gzb-k {
  stop-color: var(--svg-color--a22b2c, #a22b2c);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rkkueqbux {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 17.75a2 2 0 1 0 0-4a2 2 0 0 0 0 4");
}

.s-t63rrjo {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.73 4.75H9.27L4 19.25h4.835L9.5 17.4a3 3 0 0 1 1.6-4.51l.9-2.54l.9 2.54a3 3 0 0 1 1.605 4.51l.66 1.85H20z");
}

.s6k9lqbcf {
  stop-color: var(--svg-color--51a7dc, #51a7dc);
}

</style>
