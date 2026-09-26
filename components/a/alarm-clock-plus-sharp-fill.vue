<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="cq4jq5b9j"/><path class="ztp2ojn_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-plus-sharp-fill" /></template>
<style>
.cq4jq5b9j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4C16.9706 4 21 8.0294 21 13C21 17.9706 16.9706 22 12 22C7.0294 22 3 17.9706 3 13C3 8.0294 7.0294 4 12 4ZM11 8L11 12L7 12L7 14L11 14L11 18L13 18L13 14L17 14L17 12L13 12L13 8L11 8Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ztp2ojn_h {
  d: path("M2.75 5.3462L3 5.0627C4.1606 3.7467 5.5957 2.7013 7.2042 2L7.3953 1.9167M21.25 5.3462L21 5.0627C19.8394 3.7467 18.4043 2.7013 16.7958 2L16.6047 1.9167M8 19.9282L6.5152 22.5M16 19.9282L17.4848 22.5");
}

</style>
