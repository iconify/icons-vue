<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kcs803bjd"/><path class="ws640lbea"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cursor-fill" /></template>
<style>
.kcs803bjd {
  fill: currentColor;
  d: path("M8.3184 20.5112L3.0341 3.9139C2.8602 3.3677 3.3816 2.8558 3.9268 3.0373L20.5197 8.5617C21.1361 8.7669 21.1671 9.6243 20.5672 9.8732L13.4774 12.8146C13.3157 12.8817 13.1848 13.0065 13.1107 13.1647L9.6254 20.596C9.3541 21.174 8.5121 21.1195 8.3184 20.5112Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ws640lbea {
  d: path("M8.3184 20.5112L3.0341 3.9139C2.8602 3.3677 3.3816 2.8558 3.9268 3.0373L20.5197 8.5617C21.1361 8.7669 21.1671 9.6243 20.5672 9.8732L13.4774 12.8146C13.3157 12.8817 13.1848 13.0065 13.1107 13.1647L9.6254 20.596C9.3541 21.174 8.5121 21.1195 8.3184 20.5112Z");
}

</style>
