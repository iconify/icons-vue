<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="qbvk0cc3q"/><path class="v4cpchbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-ring-outline-regular" /></template>
<style>
.jkuojibnm {
  d: path("M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qbvk0cc3q {
  d: path("m3 9 2 -2");
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.v4cpchbya {
  d: path("m21 9 -2 -2");
}

</style>
