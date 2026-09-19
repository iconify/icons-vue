<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="zyge0lbvv"/><path class="h5u8nkbuu"/><path class="zhvmldb0f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:affluences" /></template>
<style>
.h5u8nkbuu {
  d: path("M21.863 7.822c-9.031 0-18.35 7.115-18.32 18.439S13.194 44.5 21.783 44.5s14.571-5.942 16.096-9.2l-4.645-2.744c-1.335 2.797-5.484 6.709-11.182 6.709S8.9 34.747 8.9 26.554s6.82-13.7 12.967-13.504z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zhvmldb0f {
  d: path("M28.997 30.562h-3.026l-4.056-10.787l-3.982 10.787l-2.436-.025m3.857-3.49h5.168");
}

.zyge0lbvv {
  d: path("m21.88 3.5l.004 9.553c9.53.097 13.105 8.547 13.167 13.03c.031 2.306-.97 5.116-1.817 6.47l8.18 4.839a22.43 22.43 0 0 0 3.043-11.295v-.025C44.443 13.657 34.285 3.49 21.88 3.5");
}

</style>
