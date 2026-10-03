<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGpPWQtdkC" x2="1" y1="500.09" y2="500.09" gradientTransform="rotate(-76.52 -3903.8 3088.52)scale(-12.39205 12.39205)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="l2k064n6d"/></linearGradient><linearGradient id="SVGZY284dkX" x2="1" y1="500.04" y2="500.04" gradientTransform="rotate(210.83 -779.16 2869.68)scale(-11.437 11.437)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient></defs><path class="aidonnbfy"/><path class="xqmmg7bvx"/><path class="mwxhz4b7f"/><path class="c5zi_322d"/><path class="jpxl1wcxj"/><path class="m9rilf75u"/><path fill="url(#SVGpPWQtdkC)" class="tzmuyntva"/><path fill="url(#SVGZY284dkX)" class="i7o1pw78g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-light-cypress" /></template>
<style>
.aidonnbfy {
  fill: var(--svg-color--31ad79, #31ad79);
  d: path("M29.48 5.46h-11.4l-2.1 4.2H4.28v16.8h25.2zm-2.1 4.2h-8.2l1.1-2.1h7.1Z");
}

.c5zi_322d {
  d: path("M17.13 18.03c.79 0 1.43.41 1.75 1.14l.03.05l1.32-.44l-.03-.07a3.25 3.25 0 0 0-3.07-2q-1.45 0-2.41.95q-.98.95-.98 2.35t.98 2.35q.96.94 2.41.94c1.38 0 2.56-.76 3.07-2l.03-.06l-1.32-.45l-.03.06c-.3.71-.95 1.14-1.75 1.14a2 2 0 0 1-1.37-.56A2 2 0 0 1 15.2 20a2 2 0 0 1 .56-1.42a2 2 0 0 1 1.37-.56");
}

.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.i7o1pw78g {
  d: path("m21.1 27.12l-.32.8a.4.4 0 0 1-.39.27h-.33a8.4 8.4 0 0 1-8.16-6.45l-1.32.3a9.7 9.7 0 0 0 3.37 5.36a9.8 9.8 0 0 0 6.1 2.13h.41a1.8 1.8 0 0 0 1.57-1.1l.43-1.04Z");
}

.jpxl1wcxj {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M10.7 22.54a10 10 0 0 1-.35-2.55c0-3.94 2.5-7.55 6.22-8.97l.49 1.25a8.3 8.3 0 0 0-5.35 7.72a8 8 0 0 0 .3 2.2z");
}

.l2k064n6d {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
  stop-opacity: 0;
}

.m9rilf75u {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M16.5 11.05a10 10 0 0 1 2.53-.61a9.8 9.8 0 0 1 9.65 5.2l-1.2.6a8.4 8.4 0 0 0-8.31-4.46a8 8 0 0 0-2.17.52z");
}

.mwxhz4b7f {
  d: path("m25.39 16.83l-1.88 4.72l-1.9-4.72h-1.54l2.65 6.44l-1.88 4.54l1.35.27l4.66-11.25z");
}

.tzmuyntva {
  d: path("M24.5 26.99a8.3 8.3 0 0 0 2.92-10.85l1.2-.62a9.6 9.6 0 0 1-3.4 12.6z");
}

.xqmmg7bvx {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M19.68 10.03a10 10 0 0 1 10.33 9.62a10 10 0 0 1-9.61 10.32a9.98 9.98 0 0 1-.73-19.95");
}

</style>
