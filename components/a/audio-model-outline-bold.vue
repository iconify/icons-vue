<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iaozfqbuj"/><path class="y5k8b5bfa"/><path class="w_jkatblo"/><path class="coi-np7dk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:audio-model-outline-bold" /></template>
<style>
.coi-np7dk {
  d: path("M15 9v6");
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w_jkatblo {
  d: path("M12 7v10");
}

.y5k8b5bfa {
  d: path("M9 9v6");
}

</style>
