<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qzuhyfbun"/><path class="hta_0tb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kmeet" /></template>
<style>
.hta_0tb5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.444 16.204l-3.541 2.044V15.9a1.127 1.127 0 0 0-1.128-1.127H19.247A1.13 1.13 0 0 0 18.12 15.9v9.019a1.127 1.127 0 0 0 1.127 1.127h13.528a1.127 1.127 0 0 0 1.127-1.127v-1.8l3.541 2.044a.45.45 0 0 0 .677-.39v-8.179a.45.45 0 0 0-.676-.39M9.88 14.773v11.273m.001-2.395l5.103-5.078m-3.479 3.462l4.012 3.994");
}

.qzuhyfbun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.5 5.91h-35a2 2 0 0 0-2 2v25a2 2 0 0 0 2 2h18.407l6.886 6.886a1 1 0 0 0 1.707-.707v-6.18h8a2 2 0 0 0 2-2v-25a2 2 0 0 0-2-2");
}

</style>
