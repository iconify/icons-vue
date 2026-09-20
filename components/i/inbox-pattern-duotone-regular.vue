<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kqavb5qkt"/><path class="gwlxvvbgd"/><path class="fo_-a1b-k"/><path class="f-52c6b3g"/><path class="rr985ibot"/><path class="rqm7ypbhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:inbox-pattern-duotone-regular" /></template>
<style>
.f-52c6b3g {
  d: path("M4 10v10h16V10");
}

.fo_-a1b-k {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 5.5 12 8l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gwlxvvbgd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kqavb5qkt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v10h16V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqm7ypbhc {
  d: path("M9.5 5.5 12 8l2.5 -2.5");
}

.rr985ibot {
  d: path("M12 3v2.5");
}

</style>
