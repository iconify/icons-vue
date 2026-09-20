<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVG4hTDM8QP" class="chdp54bpl"/></defs><path class="cuy5ac7ov"/><path class="m0kgkmred"/><use href="#SVG4hTDM8QP" class="e0ty9gbgt"/><path class="m8hahnerl"/><use href="#SVG4hTDM8QP" class="k0jpwu2hx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:cross-mark-button" /></template>
<style>
.chdp54bpl {
  fill: var(--svg-color--abc884, #abc884);
  d: path("M40.16 12.86c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
}

.cuy5ac7ov {
  fill: var(--svg-color--689f38, #689f38);
  d: path("M116.46 3.96h-104c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8v-104c0-4.42-3.58-8-8-8");
}

.e0ty9gbgt {
  opacity: var(--svg-opacity--0-65, 0.65);
}

.k0jpwu2hx {
  opacity: var(--svg-opacity--0-35, 0.35);
}

.m0kgkmred {
  fill: var(--svg-color--7cb342, #7cb342);
  d: path("M110.16 3.96h-98.2a7.555 7.555 0 0 0-7.5 7.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.46c.09-4.05-3.13-7.41-7.18-7.5z");
}

.m8hahnerl {
  fill: var(--svg-color--fbf9f9, #fbf9f9);
  d: path("M108.71 95.08L77.54 64.2l30.88-31.17c3.5-3.53 3.47-9.23-.06-12.73s-9.23-3.47-12.73.06L64.75 51.53L33.57 20.65c-3.53-3.5-9.23-3.47-12.73.06s-3.47 9.23.06 12.73l31.18 30.88L21.19 95.5c-3.5 3.53-3.47 9.23.06 12.73a8.95 8.95 0 0 0 6.33 2.61c2.32 0 4.63-.89 6.39-2.67l30.89-31.18l31.18 30.88a8.95 8.95 0 0 0 6.33 2.61c2.32 0 4.63-.89 6.39-2.67c3.51-3.53 3.48-9.23-.05-12.73");
}

</style>
