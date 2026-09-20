<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wmtj7ubjb"/><path class="bw1nw8b2t"/><path class="l517yxbln"/><path class="yhgzmt2de"/><path class="b-g91f0jy"/><path class="s4l_k6b-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:feels-like-outline-regular" /></template>
<style>
.b-g91f0jy {
  d: path("M16 14a3 3 0 0 1 6 0");
}

.bw1nw8b2t {
  d: path("M10 17.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l517yxbln {
  d: path("M12 9v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s4l_k6b-t {
  d: path("M3 20h4");
}

.wmtj7ubjb {
  d: path("M9.5 15V6a2.5 2.5 0 0 1 5 0v9a4.5 4.5 0 1 1 -5 0");
}

.yhgzmt2de {
  d: path("M17 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
