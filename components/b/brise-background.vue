<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGeTV04cIK)" class="r4i437pya"/><path class="gd1dw32kz"/></g><defs><linearGradient id="SVGeTV04cIK" x1="17.112" x2="6.889" y1="11.9" y2="11.9" gradientUnits="userSpaceOnUse"><stop class="wb39tmtdw"/><stop offset="1" class="cv81z0ben"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:brise-background" /></template>
<style>
.cv81z0ben {
  stop-color: var(--svg-color--8109ea, #8109ea);
}

.ft5dv1b6b {
  fill: none;
}

.gd1dw32kz {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.965 6.933a.15.15 0 0 1-.076-.128v-1.29A1.516 1.516 0 0 1 8.405 4h.178c.346 0 .689.093.986.271l6.925 4.12a1.26 1.26 0 0 1 .618 1.076v.311a1.78 1.78 0 0 1-.89 1.542l-9.066 5.258a.177.177 0 0 1-.267-.151v-8.64a.222.222 0 0 1 .334-.191l4.529 2.59a.355.355 0 0 1 0 .619l-1.511.87a.36.36 0 0 1-.356 0l-.64-.373a.09.09 0 0 0-.09.001a.09.09 0 0 0-.043.08v1.324a.09.09 0 0 0 .133.08l5.076-2.933a.09.09 0 0 0 .046-.078a.09.09 0 0 0-.046-.078L9.245 6.765a.089.089 0 0 0-.133.08v.697a.356.356 0 0 1-.534.311zM6.91 17.227a.04.04 0 0 0-.022.044v1.213A1.517 1.517 0 0 0 8.405 20h.183c.346 0 .684-.089.986-.267l6.658-3.884a1.78 1.78 0 0 0 .88-1.538a1.69 1.69 0 0 0-.884-1.48l-.547-.32a.5.5 0 0 0-.502 0l-1.734 1a.16.16 0 0 0-.057.217a.16.16 0 0 0 .057.059l.907.524a.09.09 0 0 1 .042.075a.09.09 0 0 1-.042.076L9.244 17.36a.09.09 0 0 1-.133-.076v-.786a.311.311 0 0 0-.467-.267z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wb39tmtdw {
  stop-color: var(--svg-color--3710dc, #3710dc);
}

</style>
