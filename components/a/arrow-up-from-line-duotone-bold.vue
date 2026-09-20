<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w1h-xcbkl"/><path class="h1jtp-bio"/><path class="plo1k7bci"/><path class="qdn88l2uv"/><path class="g4h6r4ykz"/><path class="h3z-uye4u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:arrow-up-from-line-duotone-bold" /></template>
<style>
.g4h6r4ykz {
  d: path("M12 4v12");
}

.h1jtp-bio {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h3z-uye4u {
  d: path("m8 8 4 -4 4 4");
}

.plo1k7bci {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 8 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qdn88l2uv {
  d: path("M7 20h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w1h-xcbkl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
