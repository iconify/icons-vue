<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c0quhbmkd"/><path fill="url(#SVG3hUBrb5C)" class="zy_lwlbee"/><path fill="url(#SVGsvsuHbmy)" class="d9vbd5amh"/><defs><linearGradient id="SVG3hUBrb5C" x1="20.424" x2="3.136" y1="12.052" y2="12.567" gradientUnits="userSpaceOnUse"><stop class="w2cgp3_xd"/><stop offset="1" class="jtfc-e_le"/></linearGradient><linearGradient id="SVGsvsuHbmy" x1="19.678" x2="3.519" y1="17.43" y2="19.513" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".54" class="ewvv1g1iw"/><stop offset="1" class="uuzg62b9s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:arc" /></template>
<style>
.c0quhbmkd {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.147 5.144a.82.82 0 0 0-.669-.344a.83.83 0 0 0-.668.334L5.057 14.57a12.5 12.5 0 0 1 3.112-1.625l4.294-6.002l4.099 5.925a12.6 12.6 0 0 1 2.895 1.404z");
}

.d9vbd5amh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M14.011 16.083c-4.279 0-8.944 2.078-10.738 3.117L3 18.788c1.83-1.06 6.593-3.188 11.011-3.188c3.924 0 5.776.735 6.331.997c.129.057.18.206.118.324a.267.267 0 0 1-.35.103c-.478-.22-2.252-.94-6.099-.94");
}

.ewvv1g1iw {
  stop-color: var(--svg-color--aeaeae, #aeaeae);
}

.ft5dv1b6b {
  fill: none;
}

.jtfc-e_le {
  stop-color: var(--svg-color--041c28, #041c28);
  stop-opacity: 0.1;
}

.uuzg62b9s {
  stop-color: var(--svg-color--1e1e1e, #1e1e1e);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w2cgp3_xd {
  stop-color: var(--svg-color--197eaf, #197eaf);
}

.zy_lwlbee {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M3.514 18.804L3 19.2c.098-.123.273-.257.514-.396c2.078-1.527 6.27-4.011 9.89-4.201c4.937-.258 8.06 1.023 7.54 2.556c-.52 1.532-4.16-.515-7.54-.515c-2.967 0-8.141 1.183-9.89 2.16");
}

</style>
