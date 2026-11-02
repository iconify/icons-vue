<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="trdjr4bpx"/><path class="r6u49xp4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.r6u49xp4a {
  d: path("M11 16c-.708 0-1.398-.271-1.872-.804A2.56 2.56 0 0 1 8.5 13.5c0-1.429 1.068-2.5 2.5-2.5a1 1 0 0 1 0 2c-.324 0-.5.175-.5.5s.176.5.5.5a1 1 0 0 1 0 2m4-5c.363 0 .724.067 1.057.213c1.21.53 1.724 1.956 1.291 3.173a2.4 2.4 0 0 1-1.291 1.401A2.6 2.6 0 0 1 15 16c-.708 0-1.398-.271-1.872-.804A2.56 2.56 0 0 1 12.5 13.5c0-1.429 1.068-2.5 2.5-2.5m0 2c-.135 0-.284.027-.378.133c-.166.187-.166.547 0 .734c.094.106.243.133.378.133s.284-.027.378-.133c.166-.187.166-.547 0-.734c-.094-.106-.243-.133-.378-.133");
}

.trdjr4bpx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v10a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
