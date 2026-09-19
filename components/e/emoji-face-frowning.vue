<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="em9m8r-6s"/><circle class="l6cd208_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-frowning" /></template>
<style>
.em9m8r-6s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.359 33.652c1.51-3.083 4.684-4.984 8.043-4.826c3.084.145 5.866 2.005 7.24 4.826M19.174 19.978a2.414 2.414 0 0 1-4.826 0c0-1.331 1.081-2.413 2.413-2.413s2.413 1.082 2.413 2.413m14.478 0a2.414 2.414 0 0 1-4.826 0c0-1.331 1.082-2.413 2.413-2.413s2.413 1.082 2.413 2.413");
}

.l6cd208_p {
  cx: 24px;
  cy: 24px;
  r: 18.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
