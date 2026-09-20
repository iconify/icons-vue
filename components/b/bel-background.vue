<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="u5xuftbok"/><path clip-rule="evenodd" class="xf215up5v"/><path class="do27l4osr"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bel-background" /></template>
<style>
.do27l4osr {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.75 6.064C4.75 4.924 5.721 4 6.862 4h4.645a5.162 5.162 0 0 1 5.035 6.3s-1.008-.482-2.58-.482h-1.46c-.243.004-1.651.023-3.06.01c-1.29-.01-2.268.882-2.268 1.914v2.44h-.727c-.97 0-1.697-.784-1.697-1.924z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u5xuftbok {
  fill: var(--svg-color--00b2fa, #00b2fa);
  d: path("M24 0H0v24h24z");
}

.xf215up5v {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.863 4a2.065 2.065 0 0 0-2.065 2.064v6.194c0 1.14.68 1.924 1.893 1.924h.485v3.754A2.065 2.065 0 0 0 9.24 20h4.849a5.161 5.161 0 0 0 2.455-9.702q.124-.55.125-1.137A5.16 5.16 0 0 0 11.51 4zm9.68 6.298c-.423-.23-1.367-.48-2.58-.48h-4.52c-1.14 0-2.267.784-2.267 1.924v2.44h4.332c2.46 0 4.518-1.58 5.036-3.884");
}

</style>
