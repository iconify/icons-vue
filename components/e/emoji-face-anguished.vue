<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ggckpcclq"/><circle class="l6cd208_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-face-anguished" /></template>
<style>
.ggckpcclq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.175 19.92a2.413 2.413 0 0 1-4.824 0c0-1.332 1.081-2.413 2.412-2.413s2.412 1.081 2.412 2.412m14.475.001a2.413 2.413 0 0 1-4.825 0c0-1.332 1.081-2.413 2.412-2.413s2.412 1.081 2.412 2.412M17.567 32.041s-.096-2.335 0-2.412c1.1-.588 3.188-.804 6.433-.804c3.216 0 5.35.224 6.433.804c.07.046 0 2.412 0 2.412zm-3.901-17.489c.392.183 2.113.933 4.152.267a5.7 5.7 0 0 0 2.846-2.11m13.67 1.843c-.392.183-2.113.933-4.152.267a5.7 5.7 0 0 1-2.846-2.11");
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
