<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dvxh2ac0w"/><path class="e4x360e0s"/><path class="pn_cnwbjb"/><circle class="yrelpprxu"/><circle class="qeqkrbbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:firefox-momo" /></template>
<style>
.dvxh2ac0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.271 24.964c7.973.328 20.12 3.564 20.12 13.507c0 2.884-2.741 6.365-10.552 6.003c-7.504-.348-14.68-8.602-14.68-16.462c-2.439-.328-3.47-3.299-3.47-3.299c5.604-3.7 2.415-9.817 7.597-12.46c-1.157-.632-2.063-2.063-2.063-2.063c4.033-3.728 6.05-2.18 11.42-2.087c.117-2.72 2.813-7.832 6.694-1.008c.857-4.432 3.858-5.347 5.851.586c3.377.399 7.762 2.18 7.762 5.44s-4.783 4.644-9.567 4.644c.094 2.556-.446 5.44-5.37.75c.234 3.775-.422 5.722-6.308.422c-2.181 2.767-2.93 6.49-2.93 6.49");
}

.e4x360e0s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.532 12.324c-.844 1.485-2.533 2.923-5.268 1.345m3.916 27.973c7.298-.272 13.131-6.274 13.131-13.639c0-4.776-2.453-8.98-6.169-11.418");
}

.pn_cnwbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.245 26.645c-5.546-1.017-5.186 1.015-6.484 3.313s-4.424.938-6.235 4.243m-4.765-5.261c-2.554.456-1.866 4.426-1.866 4.426c-3.47-1.282-5.644.282-4.502 4.174c-4.128-.687-6.479.704-5.874 4.128M29.93 21.013c.061 3.927-1.288 6.583-4.24 7.295M37.358 8.82l.186 8.008");
}

.qeqkrbbti {
  cx: 29.373px;
  cy: 10.504px;
  r: 0.75px;
  fill: currentColor;
}

.yrelpprxu {
  cx: 22.143px;
  cy: 13.34px;
  r: 0.75px;
  fill: currentColor;
}

</style>
