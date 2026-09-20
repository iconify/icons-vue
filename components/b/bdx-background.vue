<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="x-r9zwhih"/><path clip-rule="evenodd" class="e52-bn-qz"/><path clip-rule="evenodd" class="k75gmybjr"/><path class="hpa8pnbjr"/><path class="u2135db0r"/><path clip-rule="evenodd" class="mo1gg5csz"/><path class="n-kphub6q"/><path class="o_s90gbxk"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bdx-background" /></template>
<style>
.e52-bn-qz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.556a7.556 7.556 0 1 0 0-15.112a7.556 7.556 0 0 0 0 15.112M12 20a7.999 7.999 0 1 0 0-15.998A7.999 7.999 0 0 0 12 20");
}

.ft5dv1b6b {
  fill: none;
}

.hpa8pnbjr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.666 12.89a.444.444 0 0 1-.444.444h-3.138c-.418 0-.925-.031-1.307-.667v1.556c0 .489.4.889.89.889h3.11a.88.88 0 0 0 .89-.89z");
}

.k75gmybjr {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M16.444 6.444v7.778a.89.89 0 0 1-.889.888h-4.889a.89.89 0 0 1-.889-.888v-4.89c0-.488.4-.888.89-.888h4.613zm-4.889 4.222a.444.444 0 0 1 .444-.444h2.223a.444.444 0 0 1 .444.444v2.222a.444.444 0 0 1-.444.445H12a.444.444 0 0 1-.445-.445z");
}

.mo1gg5csz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.111 8.666v7.777c0 .49.4.89.89.89h4.888a.89.89 0 0 0 .889-.89v-4.889a.89.89 0 0 0-.889-.888H8.276zm4.89 4.222a.445.445 0 0 0-.445-.445H9.334a.445.445 0 0 0-.445.445v2.222a.445.445 0 0 0 .445.445h2.222A.445.445 0 0 0 12 15.11z");
}

.n-kphub6q {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.111 14.89v1.555c0 .488.4.889.89.889h3.11c.534 0 .89-.223.89-.89v-1.333a.445.445 0 0 1-.445.445H8.222c-.444 0-.848-.142-1.11-.667");
}

.o_s90gbxk {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.667 10.666H8.276l-1.165-2v6.222c.263.524.667.667 1.111.667h1.112a.445.445 0 0 1-.445-.445v-2.222a.444.444 0 0 1 .445-.445h1.333z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u2135db0r {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.889 8.444h-2.223a.89.89 0 0 0-.889.889v3.333c.383.636.89.667 1.307.667h.915a.444.444 0 0 1-.444-.445v-2.222a.444.444 0 0 1 .444-.444h.89z");
}

.x-r9zwhih {
  fill: var(--svg-color--35af3b, #35af3b);
  d: path("M24 0H0v24h24z");
}

</style>
