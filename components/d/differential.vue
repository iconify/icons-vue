<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="br4hr8m_c"/><rect class="mb2p1cbne"/><rect class="z0_3sbcgb"/><circle class="nl0pxj_sf"/><path class="kejsaeqhb"/><path class="to8m3ibcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:differential" /></template>
<style>
.br4hr8m_c {
  width: 4px;
  height: 2.5px;
  x: 2.75px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.kejsaeqhb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.48 9.57v-.38q0-.4.4-.4h.24q.4 0 .4.4v.38q0 .4.28.51q.27.11.55-.17l.27-.26q.28-.28.57 0l.16.16q.28.29 0 .57l-.26.27q-.28.28-.17.55q.11.28.51.28h.38q.4 0 .4.4v.24q0 .4-.4.4h-.38q-.4 0-.51.28q-.11.27.17.55l.26.27q.28.28 0 .57l-.16.16q-.29.28-.57 0l-.27-.26q-.28-.28-.55-.17q-.28.11-.28.51v.38q0 .4-.4.4h-.24q-.4 0-.4-.4v-.38q0-.4-.28-.51q-.27-.11-.55.17l-.27.26q-.28.28-.57 0l-.16-.16q-.28-.29 0-.57l.26-.27q.28-.28.17-.55q-.11-.28-.51-.28h-.38q-.4 0-.4-.4v-.24q0-.4.4-.4h.38q.4 0 .51-.28q.11-.27-.17-.55l-.26-.27q-.28-.28 0-.57l.16-.16q.29-.28.57 0l.27.26q.28.28.55.17q.28-.11.28-.51");
}

.mb2p1cbne {
  width: 4px;
  height: 2.5px;
  x: 17.25px;
  y: 10.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.nl0pxj_sf {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.to8m3ibcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z0_3sbcgb {
  width: 2.5px;
  height: 4px;
  x: 10.75px;
  y: 17.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

</style>
