<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGDBkoGehC" x1="-207.66" x2="-216.52" y1="160.23" y2="151.37" gradientTransform="matrix(1 0 0 -1 234 178)" gradientUnits="userSpaceOnUse"><stop offset="0" class="y5fb0lpcu"/><stop offset="1" class="ojj18acah"/></linearGradient></defs><path class="aqyi05bvb"/><path class="qyrcwyb2k"/><path fill="url(#SVGDBkoGehC)" class="fx-lqbcvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-turbo" /></template>
<style>
.aqyi05bvb {
  fill: var(--svg-color--52525b, #52525b);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.fx-lqbcvb {
  fill-rule: evenodd;
  d: path("M21.48 14.19V12a9 9 0 0 1 0 18v-2.19a6.83 6.83 0 0 0 0-13.62m-5.65 11.28a6.9 6.9 0 0 1-1.65-4H12A8.93 8.93 0 0 0 14.29 27l1.54-1.54ZM20.5 30v-2.19a6.8 6.8 0 0 1-4-1.65L15 27.7a8.93 8.93 0 0 0 5.5 2.3");
}

.ojj18acah {
  stop-color: var(--svg-color--ff1e56, #ff1e56);
}

.qyrcwyb2k {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M21 15.15A5.85 5.85 0 1 0 26.84 21A5.86 5.86 0 0 0 21 15.15M21 24a3 3 0 1 1 3-3a3 3 0 0 1-3 3");
}

.y5fb0lpcu {
  stop-color: var(--svg-color--0096ff, #0096ff);
}

</style>
