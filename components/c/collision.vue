<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="lm82v8b4t"/><radialGradient id="SVGGoNsJxos" cx="77.587" cy="75.735" r="26.365" gradientUnits="userSpaceOnUse"><stop offset="0" class="njjc-ibiz"/><stop offset="1" class="md120d8ra"/></radialGradient><path fill="url(#SVGGoNsJxos)" class="k8fmiobyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:collision" /></template>
<style>
.k8fmiobyc {
  stroke: var(--svg-color--ffeb3b, #ffeb3b);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m72.63 34.77l9.54 24.71l18.88-21.31l-14.19 29.74l17.21-5.17l-15.95 15.85l13.36 4.39l-12.8 1.89l10.19 14.44l-16.56-10.58l-3.81 12.32l-5.87-14.09l-14.65 11.16L64 84.45l-23 5.02l16.95-10.28l-22.11-10.63l24.49 2.28l-20.11-31.55L71.1 60.17z");
}

.lm82v8b4t {
  fill: var(--svg-color--ffa000, #ffa000);
  stroke: var(--svg-color--f44336, #f44336);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("m68.27 8.51l15.84 33.16l35.33-31.88l-18.06 45.64l19.67-5.31l-18.65 26.51l17.03 5.87l-17.4 8.27l16.93 29.03l-32.19-19.91l-6.9 21.54L69.65 98.4l-29 21.78l8.82-24.85l-39.97 8.04L39.42 81.1L7.89 58.4l35.96 3.11L10.6 10.52L64 45.51z");
}

.md120d8ra {
  stop-color: var(--svg-color--fff176, #fff176);
}

.njjc-ibiz {
  stop-color: var(--svg-color--fffde7, #fffde7);
}

</style>
