<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ljpui4fwa"/><path fill="url(#SVGYJthzewh)" class="ovu3ix93x"/><path fill="url(#SVGPcUOtXlK)" class="ija6hubgf"/><defs><linearGradient id="SVGYJthzewh" x1="10.318" x2="21.947" y1="5.471" y2="19.465" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="nj2vizlpw"/></linearGradient><linearGradient id="SVGPcUOtXlK" x1="17.4" x2="10.888" y1="19.637" y2="10.901" gradientUnits="userSpaceOnUse"><stop class="fk3a3gb7j"/><stop offset="1" class="da6k7acbo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dydx" /></template>
<style>
.da6k7acbo {
  stop-color: var(--svg-color--6966ff, #6966ff);
  stop-opacity: 0.36;
}

.fk3a3gb7j {
  stop-color: var(--svg-color--6966ff, #6966ff);
}

.ft5dv1b6b {
  fill: none;
}

.ija6hubgf {
  d: path("m16.52 21l-4.082-5.87l1.922-2.808L20.357 21z");
}

.ljpui4fwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.146 3L3.643 21h3.838L20.048 3z");
}

.nj2vizlpw {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.55;
}

.ovu3ix93x {
  d: path("m7.886 3l3.677 5.303l-1.922 2.893L3.965 3z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
