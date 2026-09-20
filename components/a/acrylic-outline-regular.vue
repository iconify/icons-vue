<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pccmg_b3k"/><path class="iu91ib-mt"/><path class="e-07m9b9c"/><path class="pw9d8_-zo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:acrylic-outline-regular" /></template>
<style>
.e-07m9b9c {
  d: path("M6 11h12");
}

.iu91ib-mt {
  d: path("m6 8 3 -3h6l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pccmg_b3k {
  d: path("M6 20V8h12v12Z");
}

.pw9d8_-zo {
  d: path("M10 5V2h4v3");
}

</style>
