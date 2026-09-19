<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="aazatcc4u"/><path class="n1jyjm6qs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ma-gare-sncf" /></template>
<style>
.aazatcc4u {
  cx: 24px;
  cy: 17.329px;
  r: 2.933px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n1jyjm6qs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.18 20.065L24 10.271L4.82 20.065c-.548.28-.349 1.107.266 1.107H7.09v16.557h5.721v-8.553a1.797 1.797 0 0 1 3.594 0v8.552h4.944V26.652a2.651 2.651 0 1 1 5.302 0v11.077h4.944v-8.552a1.797 1.797 0 0 1 3.594 0v8.552h5.721V21.172h2.004c.615 0 .814-.827.266-1.107");
}

</style>
