<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d-_6pilkw"/><path clip-rule="evenodd" class="kew2exbfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cast-pause-fill" /></template>
<style>
.d-_6pilkw {
  d: path("M2 8V7C2 5.343 3.343 4 5 4H12M22 14V17C22 18.657 20.657 20 19 20H14M2 16C4.209 16 6 17.791 6 20M2 12C6.418 12 10 15.582 10 20M17 4V10M21 4V10");
}

.kew2exbfm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 20C3 20.552 2.552 21 2 21C1.448 21 1 20.552 1 20C1 19.448 1.448 19 2 19C2.552 19 3 19.448 3 20Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
