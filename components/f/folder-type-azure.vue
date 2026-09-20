<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGTFKIfefH" x1="-231.442" x2="-231.459" y1="265.978" y2="265.903" gradientTransform="matrix(161.096 0 0 -241.217 37302.352 64171.913)" gradientUnits="userSpaceOnUse"><stop offset="0" class="sezoddb5r"/><stop offset="1" class="te6563h5y"/></linearGradient><linearGradient id="SVGwVxTteGX" x1="-231.869" x2="-231.875" y1="265.942" y2="265.94" gradientTransform="matrix(224.69 0 0 -241.214 52119.718 64171.207)" gradientUnits="userSpaceOnUse"><stop offset="0" class="p_qts-b_r"/><stop offset=".071" class="a2gzbfbcc"/><stop offset=".321" class="tipw_dbaw"/><stop offset=".623" class="ws0rd4b2v"/><stop offset="1" class="k05n1gbkm"/></linearGradient><linearGradient id="SVGlRtw2dYZ" x1="-232.004" x2="-231.984" y1="265.98" y2="265.906" gradientTransform="matrix(169.755 0 0 -241.217 39406.126 64171.912)" gradientUnits="userSpaceOnUse"><stop offset="0" class="l3_3-ephw"/><stop offset="1" class="ms0tavq2o"/></linearGradient></defs><path class="bwm55kgus"/><path fill="url(#SVGTFKIfefH)" class="o9fx26b_b"/><path class="swrumyzar"/><path fill="url(#SVGwVxTteGX)" class="pdnotzbxi"/><path fill="url(#SVGlRtw2dYZ)" class="ih_yqibye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-azure" /></template>
<style>
.a2gzbfbcc {
  stop-opacity: 0.2;
}

.bwm55kgus {
  fill: var(--svg-color--5799b5, #5799b5);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.ih_yqibye {
  d: path("M24.769 12.767a.94.94 0 0 0-.894-.642h-6.607a.94.94 0 0 1 .894.642L23.9 29.754A.944.944 0 0 1 23 31h6.606a.944.944 0 0 0 .894-1.246Z");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.l3_3-ephw {
  stop-color: var(--svg-color--3ccbf4, #3ccbf4);
}

.ms0tavq2o {
  stop-color: var(--svg-color--2892df, #2892df);
}

.o9fx26b_b {
  d: path("M17.2 12.125h5.928l-6.156 18.232a.945.945 0 0 1-.9.643h-4.608a.944.944 0 0 1-.894-1.245l5.73-16.987a.945.945 0 0 1 .9-.643");
}

.p_qts-b_r {
  stop-opacity: 0.3;
}

.pdnotzbxi {
  d: path("M17.2 12.125a.94.94 0 0 0-.9.655l-5.723 16.959A.942.942 0 0 0 11.466 31H16.2a1.01 1.01 0 0 0 .776-.66l1.141-3.364l4.077 3.8A.97.97 0 0 0 22.8 31h5.3l-2.326-6.646h-6.78l4.149-12.23Z");
}

.sezoddb5r {
  stop-color: var(--svg-color--114a8b, #114a8b);
}

.swrumyzar {
  fill: var(--svg-color--0078d4, #0078d4);
  d: path("M25.811 24.354h-9.4a.435.435 0 0 0-.3.753l6.04 5.637A.95.95 0 0 0 22.8 31h5.322Z");
}

.te6563h5y {
  stop-color: var(--svg-color--0669bc, #0669bc);
}

.tipw_dbaw {
  stop-opacity: 0.1;
}

.ws0rd4b2v {
  stop-opacity: 0.05;
}

</style>
