<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ed0f25gft"/><path class="zc_lgp0dz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-arrow-right-fill" /></template>
<style>
.ed0f25gft {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 7C2 5.343 3.343 4 5 4H19C20.657 4 22 5.343 22 7L12.707 11C12.285 11.282 11.715 11.282 11.293 11L2 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zc_lgp0dz {
  d: path("M12 20H5C3.343 20 2 18.657 2 17V7M2 7C2 5.343 3.343 4 5 4H19C20.657 4 22 5.343 22 7M2 7L11.293 11C11.715 11.282 12.285 11.282 12.707 11L22 7M22 7V10M16 17H22M19 20L22 17L19 14");
}

</style>
