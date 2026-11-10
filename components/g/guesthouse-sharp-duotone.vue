<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ckukcwbji"/><path class="sv2_0u0yl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guesthouse-sharp-duotone" /></template>
<style>
.ckukcwbji {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22.86 2L22.998 3.99L21 4.13V17C21 17.55 20.552 18 20 18H4C3.448 18 3 17.55 3 17V5.9L1.199 6.08L1 4.09L3 3.89V2H5V3.69L19.921 2.2L22.86 2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.sv2_0u0yl {
  d: path("M15 20V22H9V20H15ZM12.099 12C13.105 12.11 14 12.97 14 14V16H10V14C10 12.9 10.995 12 12.099 12ZM8 8C8.552 8 9 8.45 9 9C9 9.55 8.552 10 8 10C7.448 10 7 9.55 7 9C7 8.45 7.448 8 8 8Z");
}

</style>
