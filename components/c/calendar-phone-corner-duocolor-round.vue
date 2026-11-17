<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cvr5in58m"/><path class="atkmu9bjw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-phone-corner-duocolor-round" /></template>
<style>
.atkmu9bjw {
  d: path("M9 21H8a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4M8 3v2m8-2v2M4 9h16");
}

.cvr5in58m {
  stroke-opacity: 0.4;
  d: path("M13 13.889c0-.491.398-.889.889-.889h.444c.752 0 1.456.528 1.778 1.333c.308.77.308 1.47 0 1.778a.943.943 0 0 0 0 1.333l.889.89a.943.943 0 0 0 1.333 0c.285-.285.765-.445 1.334-.445h.444c.491 0 .889.796.889 1.778v.444a.89.89 0 0 1-.889.889A7.11 7.11 0 0 1 13 13.889");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
