<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGFDAQkchI" x2="1" y1="500.02" y2="500.02" gradientTransform="rotate(105.4 -2109.4 -2759.12)scale(11.1149 -11.1149)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1"/></linearGradient><linearGradient id="SVGwtR70beF" x2="1" y1="500.07" y2="500.07" gradientTransform="matrix(8.73082 6.88 6.88 -8.73082 -3428.72 4388.35)" gradientUnits="userSpaceOnUse"><stop offset="0" class="cxqk8zbds"/><stop offset="1" class="d9ofppbqf"/></linearGradient></defs><path class="e6ozi334g"/><path class="tik92kbab"/><path class="embftkbie"/><path class="wb3bkf_dy"/><path fill="url(#SVGFDAQkchI)" class="tzmuyntva"/><path class="jpxl1wcxj"/><path class="m9rilf75u"/><path fill="url(#SVGwtR70beF)" class="uawrecchk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-cypress-opened" /></template>
<style>
.cxqk8zbds {
  stop-color: var(--svg-color--58d09e, #58d09e);
}

.d9ofppbqf {
  stop-color: var(--svg-color--d2d2d2, #d2d2d2);
}

.e6ozi334g {
  fill: var(--svg-color--31ad79, #31ad79);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21zm-7.2 2.1h7.1v2.1h-8.1zm5.5 6.1H6.6v-1.9h20.8v7.63z");
}

.embftkbie {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m25.39 16.83l-1.88 4.72l-1.9-4.72h-1.54l2.65 6.44l-1.88 4.54l1.35.27l4.66-11.25z");
}

.jpxl1wcxj {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M10.7 22.54a10 10 0 0 1-.35-2.55c0-3.94 2.5-7.55 6.22-8.97l.49 1.25a8.3 8.3 0 0 0-5.35 7.72a8 8 0 0 0 .3 2.2z");
}

.m9rilf75u {
  fill: var(--svg-color--58d09e, #58d09e);
  d: path("M16.5 11.05a10 10 0 0 1 2.53-.61a9.8 9.8 0 0 1 9.65 5.2l-1.2.6a8.4 8.4 0 0 0-8.31-4.46a8 8 0 0 0-2.17.52z");
}

.tik92kbab {
  d: path("M19.68 10.03a10 10 0 0 1 10.33 9.62a10 10 0 0 1-9.61 10.32a9.98 9.98 0 0 1-.73-19.95");
}

.tzmuyntva {
  d: path("M24.5 26.99a8.3 8.3 0 0 0 2.92-10.85l1.2-.62a9.6 9.6 0 0 1-3.4 12.6z");
}

.uawrecchk {
  d: path("m21.1 27.17l-.33.8a.4.4 0 0 1-.39.26l-.33.01a8.4 8.4 0 0 1-8.16-6.45l-1.32.3a9.6 9.6 0 0 0 3.37 5.35a9.8 9.8 0 0 0 6.1 2.14h.41a1.8 1.8 0 0 0 1.57-1.1l.43-1.04z");
}

.wb3bkf_dy {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("M17.13 18.03c.79 0 1.43.41 1.75 1.14l.03.05l1.32-.44l-.03-.07a3.25 3.25 0 0 0-3.07-2q-1.45 0-2.41.95q-.98.95-.98 2.35t.98 2.35q.96.94 2.41.94c1.38 0 2.56-.76 3.07-2l.03-.06l-1.32-.45l-.03.06c-.3.71-.95 1.14-1.75 1.14a2 2 0 0 1-1.37-.56A2 2 0 0 1 15.2 20a2 2 0 0 1 .56-1.42a2 2 0 0 1 1.37-.56");
}

</style>
