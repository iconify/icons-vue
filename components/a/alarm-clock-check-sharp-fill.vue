<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="vndk8uiaj"/><path class="ztp2ojn_h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:alarm-clock-check-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vndk8uiaj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 4C16.9706 4 21 8.0294 21 13C21 17.9706 16.9706 22 12 22C7.0294 22 3 17.9706 3 13C3 8.0294 7.0294 4 12 4ZM8.1601 13.9599L10.6543 16.5255C10.8426 16.7191 11.1012 16.8284 11.3713 16.8284C11.7197 16.8284 12.0429 16.6471 12.2246 16.3499L15.9741 10.2145L14.2676 9.1716L11.1901 14.2073L9.5941 12.5657Z");
  stroke: none;
}

.ztp2ojn_h {
  d: path("M2.75 5.3462L3 5.0627C4.1606 3.7467 5.5957 2.7013 7.2042 2L7.3953 1.9167M21.25 5.3462L21 5.0627C19.8394 3.7467 18.4043 2.7013 16.7958 2L16.6047 1.9167M8 19.9282L6.5152 22.5M16 19.9282L17.4848 22.5");
}

</style>
