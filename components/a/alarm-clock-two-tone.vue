<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w4srdrbby"/><path class="wz5gcy2rh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w4srdrbby {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4C16.9706 4 21 8.0294 21 13C21 17.9706 16.9706 22 12 22C7.0294 22 3 17.9706 3 13C3 8.0294 7.0294 4 12 4Z");
  stroke: none;
}

.wz5gcy2rh {
  d: path("M12 5C16.4183 5 20 8.5817 20 13C20 17.4183 16.4183 21 12 21C7.5817 21 4 17.4183 4 13C4 8.5817 7.5817 5 12 5ZM12 9L12 13L16 13M3 5.0627C4.1606 3.7467 5.5957 2.7013 7.2042 2M21 5.0627C19.8394 3.7467 18.4043 2.7013 16.7958 2M8 19.9282L6.8038 22M16 19.9282L17.1962 22");
}

</style>
