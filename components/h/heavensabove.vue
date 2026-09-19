<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="duqlzzbjl"/><path class="ev_k7obau"/><path class="s77mtwbaj"/><path class="b-6guxcdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:heavensabove" /></template>
<style>
.b-6guxcdv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.3 13.3l-1.8 1l-1 1.8l-1-1.8l-1.8-1l1.8-1l1-1.8l1 1.8Zm-9.6-3.4l-1.3.7l-.7 1.3l-.7-1.3l-1.3-.7l1.3-.7l.7-1.2l.7 1.3Zm18.7 6.2l-1 .5l-.5 1l-.5-1l-1-.5l1-.5l.5-1l.5 1Zm-27.1 3.6l-1 .5l-.5 1l-.5-1l-1-.5l1-.5l.5-1l.5 1Z");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.duqlzzbjl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M44.1 31.6a21.48 21.48 0 0 0-38.5 3.5");
}

.ev_k7obau {
  fill: none;
  stroke: currentColor;
  d: path("M13.5 42.8c-.5-2.3-.2-3.8 1.7-5.2a3.67 3.67 0 0 0 1.3-1.8a2.1 2.1 0 0 1 1.3-1.3A6.38 6.38 0 0 1 22 34c1.5.6 2.2 1.8 3.4 2.3a3.08 3.08 0 0 0 2.3.1c2.1-1 3.4.2 4.2 1.6a36.5 36.5 0 0 0 3.1 4.3");
}

.s77mtwbaj {
  fill: none;
  stroke: currentColor;
  d: path("M29.7 36.1c-.1-1.8.5-2.5-1.1-2.5c-.7 0-1.7 0-2-.5c-.4-1-.8-1-1.5-1.2a3.3 3.3 0 0 0-1.9-.3c-.3.1.3 1.6-.5 1.5c-.4-.1-.9-1.8-1.6-2.3a2.32 2.32 0 0 0-2.5.4c-1.4 1.3-2.3 1.6-3.2 1.1c-.6-.3-.3-2.1.1-2.4c.9-.6 1.3 0 2-1c.2-.3-.3-1 .2-1.9s2.5 0 3.3-1.1s2.8-2.7 4.4-1.6a4.4 4.4 0 0 0 1 .6c.3.2.6-.6 1-1s.6-.3 1.3-.3a17.4 17.4 0 0 0 3.4-1.3");
}

</style>
