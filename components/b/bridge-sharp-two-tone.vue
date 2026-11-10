<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p9l1zrhbp"/><path class="u2sgnh5bc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bridge-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9l1zrhbp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3V6.797C7.88 8.787 9.933 10 12 10C14.067 10 16.12 8.787 17 6.797V3H19V6.685C19.412 7.276 19.8 7.733 20.25 8.094C20.75 8.494 21.365 8.811 22.242 9.03L23 9.22L22.515 11.159L21.758 10.97C20.775 10.724 19.975 10.362 19.288 9.873L19 9.656V15H23V17H19V21H17V17H7V21H5V17H1V15H5V9.656L4.712 9.873C4.025 10.362 3.225 10.724 2.242 10.97L1.485 11.159L1 9.22L1.758 9.03C2.635 8.811 3.25 8.494 3.75 8.094C4.2 7.733 4.588 7.276 5 6.685V3H7Z");
  stroke: none;
}

.u2sgnh5bc {
  d: path("M6 3V7M6 7V16M6 7C7 9.5 9.5 11 12 11M6 7C5 8.5 4 9.5 2 10L1.243 10.189M6 16V21M6 16H1M6 16H12M12 11C14.5 11 17 9.5 18 7M12 11V16M12 16H18M18 7V3M18 7V16M18 7C19 8.5 20 9.5 22 10L22.757 10.189M18 16V21M18 16H23");
}

</style>
