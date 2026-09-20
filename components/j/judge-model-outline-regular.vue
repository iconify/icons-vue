<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ozi-k-boi"/><path class="d23kmtbkz"/><path class="efyfmvbkh"/><path class="x5li7lwaz"/><path class="jwnes9bsk"/><path class="nijl6gb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:judge-model-outline-regular" /></template>
<style>
.d23kmtbkz {
  d: path("M9 7a3 3 0 0 1 -6 0");
}

.efyfmvbkh {
  d: path("M21 7a3 3 0 0 1 -6 0");
}

.jwnes9bsk {
  d: path("M8 19h8");
}

.nijl6gb2v {
  d: path("M17 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.x5li7lwaz {
  d: path("M12 7v12");
}

</style>
