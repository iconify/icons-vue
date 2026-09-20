<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f26_egfpr"/><path class="wl451lb4h"/><path class="y1-pezfox"/><path class="iij-e10lc"/><path class="betgqmbiv"/><path class="phj2v-bip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:card-index-dividers" /></template>
<style>
.betgqmbiv {
  fill: var(--svg-color--f18f26, #f18f26);
  d: path("M17 7h-5a2 2 0 0 0-2 2v1h2a2 2 0 0 1 2 2h3a2 2 0 0 0 2-2V9a2 2 0 0 0-2-2");
}

.f26_egfpr {
  fill: var(--svg-color--fdcb58, #fdcb58);
  d: path("M31 15a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h22a2 2 0 0 1 2 2z");
}

.iij-e10lc {
  fill: var(--svg-color--78b159, #78b159);
  d: path("M23 3h-5a2 2 0 0 0-2 2v1h2a2 2 0 0 1 2 2h3a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2");
}

.phj2v-bip {
  fill: var(--svg-color--9268ca, #9268ca);
  d: path("M13 14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2z");
}

.wl451lb4h {
  fill: var(--svg-color--fdd888, #fdd888);
  d: path("M33 19a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h26a2 2 0 0 1 2 2z");
}

.y1-pezfox {
  fill: var(--svg-color--fee7b8, #fee7b8);
  d: path("M35 33a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V15a2 2 0 0 1 2-2h30a2 2 0 0 1 2 2z");
}

</style>
