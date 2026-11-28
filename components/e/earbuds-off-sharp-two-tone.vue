<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="luapt600u"/><path class="wc95qeryy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.luapt600u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 11V19C11 20.657 9.657 22 8 22C6.343 22 5 20.657 5 19V11.899C2.672 11.424 0.999 9.376 0.999 7C0.999 5.426 1.741 3.944 3 3L11 11ZM19 19C19 20.657 17.657 22 16 22C14.343 22 13 20.657 13 19V13L19 19ZM5.749 2.006C5.832 2.002 5.916 2 6 2C8.761 2 11 4.238 11 7V7.257L5.749 2.006ZM13 9.257V7C13 4.238 15.239 2 18 2C20.761 2 23 4.238 23 7C23 9.376 21.328 11.424 19 11.899V15.257L13 9.257Z");
  stroke: none;
}

.wc95qeryy {
  d: path("M3.716 3.716C2.679 4.439 2 5.64 2 7C2 9.209 3.791 11 6 11V19C6 20.105 6.895 21 8 21C9.105 21 10 20.105 10 19V10M14 14V19C14 20.105 14.895 21 16 21C17.105 21 18 20.105 18 19V18M6 17H10M14 17H17M1.707 1.707L22.293 22.293");
}

</style>
