<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l9nv_wlif"/><path class="wph7lpbsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm-certified" /></template>
<style>
.l9nv_wlif {
  d: path("M12 3.5a2.5 2.5 0 0 1 4.25 1.75A2.5 2.5 0 0 1 18 9.5a2.5 2.5 0 0 1-1.75 4.25A2.5 2.5 0 0 1 12 15.5a2.5 2.5 0 0 1-4.25-1.75A2.5 2.5 0 0 1 6 9.5a2.5 2.5 0 0 1 1.75-4.25A2.5 2.5 0 0 1 12 3.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wph7lpbsg {
  d: path("M7.75 13.75L6 21l2.25-1.25L10 21l2-5.5m4.25-1.75L18 21l-2.25-1.25L14 21l-2-5.5m0-2.75v-3.5m0 .75c-2 0-2.75-1.25-2.75-2.5C11 7.5 12 8.5 12 10Zm0-.75Q12 7 14.25 7q0 2.25-2.25 2.25Z");
}

</style>
