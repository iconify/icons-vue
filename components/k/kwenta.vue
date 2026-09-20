<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG9DxWZbvo)" class="l2o3t0lae"/><path fill="url(#SVG9rcsncuN)" class="q-qmrbbsq"/><path fill="url(#SVGwBcXZ5RQ)" class="qq1fkzanv"/><path fill="url(#SVG9C0LFbwW)" class="n5uexoh9j"/><defs><linearGradient id="SVG9DxWZbvo" x1="3" x2="20.996" y1="9.429" y2="8.984" gradientUnits="userSpaceOnUse"><stop class="d8vrfk-cj"/><stop offset="1" class="dtmhzusit"/></linearGradient><linearGradient id="SVG9rcsncuN" x1="3" x2="20.996" y1="13.457" y2="13.889" gradientUnits="userSpaceOnUse"><stop class="yk0f83n3c"/><stop offset="1" class="eodgecb4m"/></linearGradient><linearGradient id="SVGwBcXZ5RQ" x1="3" x2="22.028" y1="9.428" y2="10.734" gradientUnits="userSpaceOnUse"><stop class="car3btb1d"/><stop offset="1" class="d_wzpg_av"/></linearGradient><linearGradient id="SVG9C0LFbwW" x1="21" x2="11.471" y1="13.852" y2="14.382" gradientUnits="userSpaceOnUse"><stop class="k3qhy-b0p"/><stop offset="1" class="mjn44l7oz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kwenta" /></template>
<style>
.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.d_wzpg_av {
  stop-color: var(--svg-color--353535, #353535);
}

.d8vrfk-cj {
  stop-color: var(--svg-color--c39a6f, #c39a6f);
}

.dtmhzusit {
  stop-color: var(--svg-color--9a6a3a, #9a6a3a);
}

.eodgecb4m {
  stop-color: var(--svg-color--ae8351, #ae8351);
}

.ft5dv1b6b {
  fill: none;
}

.k3qhy-b0p {
  stop-color: var(--svg-color--373737, #373737);
}

.l2o3t0lae {
  d: path("m3 14.118l9-5.633V3L3 8.633z");
}

.mjn44l7oz {
  stop-color: var(--svg-color--2a2a2c, #2a2a2c);
}

.n5uexoh9j {
  d: path("m21 9.882l-9 5.633V21l9-5.633z");
}

.q-qmrbbsq {
  d: path("m21 14.118l-9-5.633V3l9 5.633z");
}

.qq1fkzanv {
  d: path("m3 9.882l9 5.633V21l-9-5.633z");
}

.yk0f83n3c {
  stop-color: var(--svg-color--c29665, #c29665);
}

</style>
