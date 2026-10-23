<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGSQNJybqi" x1="16" x2="16" y1="2.04" y2="30" gradientUnits="userSpaceOnUse"><stop offset="0" class="ve_g0xbpo"/><stop offset="1" class="bcuiffgri"/></linearGradient></defs><path fill="url(#SVGSQNJybqi)" class="iu0_bvb-e"/><g class="v27f9cbzg"><path class="re3z6ub_o"/><path class="maey3hbck"/></g><g class="v27f9cbzg"><path class="hfxul2s-e"/><path class="yw6xnib3q"/></g><path class="rgedi1bwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-haxedevelop" /></template>
<style>
.bcuiffgri {
  stop-color: var(--svg-color--2781c4, #2781c4);
}

.hfxul2s-e {
  d: path("M16 2.04h.087v27.9H16Zm12.5 0h.087v27.9H28.5Zm-25.1 0h.087v27.9H3.4Z");
}

.iu0_bvb-e {
  d: path("M30 30H2.04V2.04H30V16Z");
}

.maey3hbck {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-dasharray: 0.037 .413;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-091px, 0.091px);
  d: path("M2.045 12.856h27.914M2.043 6.575h27.914M2.044 9.716h27.914m-27.912 9.42H29.96m-27.914 3.14H29.96M2.046 25.418H29.96");
}

.re3z6ub_o {
  d: path("M2.04 16h27.9v.087H2.04Zm.01-12.61h27.9v.087H2.05Zm0 25.11h27.9v.087H2.05Z");
}

.rgedi1bwg {
  fill: var(--svg-color--fff, #fff);
  d: path("M29.3 26.4H2.7v.7h26.6ZM16 6.1V4.81L3 26.41h.831Zm-8.2 8.02l-.743-.524l-4.34 12.8h.83ZM16 6.1V4.81l-8.94 8.78l.743.524Zm12.2 20.3h.831l-13-21.6v1.29Zm.281 0h.855l-4.37-12.8l-.743.524Zm-4.26-12.3l.743-.524l-8.94-8.78v1.29Zm-7.14 8.61h-9.26v-.93h9.26Zm-5.56 1.39h-4.86v.93h4.86Zm9.48 0h-8.1v.93h8.1Zm4.63 0h-3.48v.93h3.48Zm-1.39-2.33h-5.79v.93h5.79Z");
}

.v27f9cbzg {
  fill: var(--svg-color--fff, #fff);
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ve_g0xbpo {
  stop-color: var(--svg-color--459fe2, #459fe2);
}

.yw6xnib3q {
  fill: none;
  stroke: var(--svg-color--fff, #fff);
  stroke-dasharray: 0.038 .412;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-09px, 0.09px);
  d: path("M19.139 2.054v27.905m3.14-27.912v27.904m3.14-27.904v27.904M12.86 2.056V29.96M9.719 2.048v27.904M6.579 2.05v27.904");
}

</style>
