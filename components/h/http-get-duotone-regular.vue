<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wywiukbgn"/><path class="ku_telleq"/><path class="etwkwy7ih"/><path class="j868g7ged"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="q8d90--8n"/><path class="bfi7-obrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:http-get-duotone-regular" /></template>
<style>
.bfi7-obrv {
  d: path("M9.5 11.5 12 14l2.5 -2.5");
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.etwkwy7ih {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8.5V14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.j868g7ged {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9.5 11.5 12 14l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ku_telleq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q8d90--8n {
  d: path("M12 8.5V14");
}

.wywiukbgn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
