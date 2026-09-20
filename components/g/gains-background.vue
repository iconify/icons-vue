<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGLAkKzbvV)" class="r4i437pya"/><path class="a64_10-se"/><path class="hcl398b6n"/><path class="qhudzqb1x"/></g><defs><linearGradient id="SVGLAkKzbvV" x1="12" x2="12" y1="3.999" y2="20.001" gradientUnits="userSpaceOnUse"><stop class="k7_7d3b6l"/><stop offset="1" class="wps4-ebhe"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gains-background" /></template>
<style>
.a64_10-se {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.7 9.781c-.449-.037-.657-.053-1.078.182a1842 1842 0 0 0-5.974 3.307c-.298.181-.62.321-.955.416c-1.51.314-2.848-1.12-2.304-2.518c.277-.715.71-.933 1.472-1.355Q10.757 7.095 15.67 4.4c1.013-.554 1.979-.533 2.907.075c.524.324.905.835 1.067 1.43c.064.245.096.693.09 1.333v10.556c0 1.104-.73 2.16-1.91 2.203c-.32.01-.64.01-.933-.107a2.53 2.53 0 0 1-1.424-2.187v-6.635c0-.55-.074-.96-.56-1.227a.5.5 0 0 0-.208-.059");
}

.ft5dv1b6b {
  fill: none;
}

.hcl398b6n {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.822 19.601a6.2 6.2 0 0 1-2.78-1.445c-.175-.16-.373-.342-.415-.566c-.075-.373.202-.555.506-.725l2.657-1.483c.33-.187.757-.075.906.267c.038.08.038.213.038.41v2.806q0 .36-.096.512c-.176.283-.491.304-.816.224m3.813-9.825c-.405-.037-.613-.037-1.013.187a1869 1869 0 0 0-5.974 3.307a3.8 3.8 0 0 1-.955.416c-1.51.314-2.848-1.12-2.304-2.518c.197-.507.474-.763.89-1.024c2.828-.923 7.361-1.878 9.356-.373z");
}

.k7_7d3b6l {
  stop-color: var(--svg-color--4af78b, #4af78b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qhudzqb1x {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.528 9.766l.171.016c.085.005.16.026.213.053c.427.24.534.555.55 1.003c.07-4.288-3.34-3.984-4.587-3.798L5.86 9.814l-.075.043a9 9 0 0 0-.496.282c2.8-.923 7.265-1.867 9.238-.373");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.wps4-ebhe {
  stop-color: var(--svg-color--23bfef, #23bfef);
}

</style>
