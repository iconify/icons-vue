<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hey48vb4g"/><path class="odev0drkd"/><path class="qm8n5-bbh"/><path class="a5-k39wji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lego-builder" /></template>
<style>
.a5-k39wji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.766 21.988V20.35a.383.383 0 0 0-.382-.383h-4.767a.383.383 0 0 0-.383.383v1.64m-10.107-4.943L12.502 6.38l8.87 1.143l-1.374 10.667zm8.524-9.862l.211-1.637a.385.385 0 0 0-.333-.431l-4.76-.614a.385.385 0 0 0-.431.333l-.211 1.637");
}

.hey48vb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.71 32.744v-1.64a.383.383 0 0 0-.382-.382h-4.767a.383.383 0 0 0-.383.383v1.64");
}

.odev0drkd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.472 32.744H10.583V43.5h26.834V32.744zm-10.65-10.756V20.35a.383.383 0 0 0-.383-.383h-4.767a.383.383 0 0 0-.383.383v1.64");
}

.qm8n5-bbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.528 21.988h-8.945v10.756h17.889V21.988z");
}

</style>
