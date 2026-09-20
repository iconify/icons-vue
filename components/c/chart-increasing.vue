<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGuLmKZbrR" class="wky3yybkm"/></defs><use href="#SVGuLmKZbrR" class="i2v6ey-hu"/><path class="sac9q07nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:chart-increasing" /></template>
<style>
.i2v6ey-hu {
  fill: var(--svg-color--ed6c30, #ed6c30);
}

.sac9q07nl {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M122.08 128H2.2c-1.21 0-2.2-.99-2.2-2.2V6.73a2.2 2.2 0 0 1 4.4 0v116.86h117.67c1.22 0 2.21.99 2.21 2.2s-.98 2.21-2.2 2.21");
}

.wky3yybkm {
  d: path("M123.04 6.67a3.854 3.854 0 0 0-5.37-.96L95.63 21.1c-.67.46-1.17 1.13-1.44 1.9L84.08 52.03L66.76 20.6a3.88 3.88 0 0 0-3.73-1.98a3.86 3.86 0 0 0-3.31 2.63l-24.4 73.97l-11.9-9.96a3.856 3.856 0 0 0-5.23.26L2.3 101.73v9.46a3.8 3.8 0 0 0 2.66-1.15L21.2 93.48l13.52 11.31a3.86 3.86 0 0 0 6.14-1.75l23.41-70.96L81.5 63.34a3.83 3.83 0 0 0 3.71 1.98a3.85 3.85 0 0 0 3.32-2.57l12.54-36.03l21.02-14.67a3.874 3.874 0 0 0 .95-5.38");
}

</style>
