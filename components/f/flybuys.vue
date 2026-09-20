<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="n99xf5b_q"/><path class="o37o4zb3e"/><path class="gg56_8bra"/><path class="jlyultbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flybuys" /></template>
<style>
.gg56_8bra {
  d: path("M34.409 21.783v2.766c0 .926-.74 1.676-1.652 1.676s-1.652-.75-1.652-1.676v-2.766");
}

.jlyultbfy {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.n99xf5b_q {
  d: path("M26.078 21.779v2.766c0 .925.74 1.676 1.652 1.676c.913 0 1.652-.75 1.652-1.676v-2.766m0 2.766v1.676m6.854-.375c.301.257.627.375 1.358.375h.371c.603 0 1.092-.497 1.092-1.11S38.568 24 37.965 24h-.741a1.1 1.1 0 0 1-1.092-1.11c0-.614.489-1.111 1.092-1.111h.37c.732 0 1.057.118 1.359.375m-25.108-2.638v5.867c0 .463.37.838.826.838h.248m4.411-1.672v2.263c0 .925-.74 1.676-1.653 1.676c-.456 0-.869-.188-1.168-.491");
}

.o37o4zb3e {
  d: path("M19.33 21.783v2.766c0 .926-.74 1.676-1.653 1.676c-.912 0-1.652-.75-1.652-1.676v-2.766m5.027 1.672c0-.926.74-1.676 1.652-1.676s1.652.75 1.652 1.676v1.09c0 .925-.74 1.676-1.652 1.676c-.913 0-1.652-.75-1.652-1.676m0 1.676v-6.705m-11.13 6.701v-5.532c0-.648.518-1.173 1.157-1.173c.569 0 .924.171 1.168.491m-3.304 1.772h2.313m23.153 2.774v2.263c0 .925-.74 1.676-1.652 1.676c-.456 0-.87-.188-1.168-.491");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
