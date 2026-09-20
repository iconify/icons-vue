<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGCdTtIM4o)" class="bcyiyzb_a"/><path fill="url(#SVGB6BcucMR)" class="bt30plbus"/><defs><linearGradient id="SVGCdTtIM4o" x1="18.604" x2="6.611" y1="8.044" y2="18.357" gradientUnits="userSpaceOnUse"><stop class="ny8_cjbux"/><stop offset=".35" class="qgoon5b_c"/><stop offset="1" class="ai1d9gm2m"/></linearGradient><linearGradient id="SVGB6BcucMR" x1="18.088" x2="18.088" y1="4.587" y2="10.411" gradientUnits="userSpaceOnUse"><stop class="wf9ik6b-q"/><stop offset="1" class="e6aqddble"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ctr" /></template>
<style>
.ai1d9gm2m {
  stop-color: var(--svg-color--c746a6, #c746a6);
}

.bcyiyzb_a {
  d: path("M16.701 11.469a5.373 5.373 0 0 1-4.982 7.306c-2.954 0-5.347-2.404-5.347-5.363a5.352 5.352 0 0 1 6.168-5.305l1.398-4.203A8.455 8.455 0 0 0 3 11.998c0 4.68 3.78 8.471 8.439 8.471a8.455 8.455 0 0 0 8.418-9z");
}

.bt30plbus {
  d: path("M18.088 10.41a2.912 2.912 0 1 0 0-5.823a2.912 2.912 0 0 0 0 5.824");
}

.e6aqddble {
  stop-color: var(--svg-color--904ee8, #904ee8);
}

.ft5dv1b6b {
  fill: none;
}

.ny8_cjbux {
  stop-color: var(--svg-color--6c7af1, #6c7af1);
}

.qgoon5b_c {
  stop-color: var(--svg-color--8958eb, #8958eb);
}

.wf9ik6b-q {
  stop-color: var(--svg-color--32c5ff, #32c5ff);
}

</style>
