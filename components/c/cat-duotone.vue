<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s9j34ebna"/><path class="eiqq58bsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cat-duotone" /></template>
<style>
.eiqq58bsm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 20c-2 0-3.7-1.2-5-3c-.6-.8-1-2.5-1-4c0-2.5-1-4-1-6s0-4 1-4s2 2 4 4h4c2-2 3-4 4-4s1 2 1 4s-1 3.5-1 6c0 1.5-.4 3.2-1 4c-1.3 1.8-3 3-5 3m-9-7l5 1m-5 4l4-1m14-4l-5 1m5 4l-4-1m-8-6h.01M15 11h.01M11 14h2l-1 1Z");
}

.ft5dv1b6b {
  fill: none;
}

.s9j34ebna {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10.422 6h3.156a29 29 0 0 0 1.554-1.809c.204-.252.407-.504.617-.75c.377-.442.784-.893 1.297-1.179c.564-.314 1.242-.37 1.806-.025c.231.141.421.339.567.566c.472.734.536 1.842.565 2.695C20 5.998 20 6.499 20 7a8 8 0 0 1-.159 1.544c-.187.957-.506 1.883-.686 2.842A9 9 0 0 0 19 13c0 .843-.102 1.683-.304 2.501c-.181.736-.437 1.487-.896 2.099c-1.379 1.909-3.355 3.399-5.8 3.4c-2.46-.001-4.424-1.495-5.811-3.415c-.455-.607-.706-1.355-.885-2.084A10.4 10.4 0 0 1 5 13a9 9 0 0 0-.155-1.614c-.18-.959-.499-1.885-.686-2.842A8 8 0 0 1 4 7c0-.501 0-1.002.016-1.502c.036-1.06.12-2.641 1.132-3.261A1.63 1.63 0 0 1 6 2c.336 0 .662.1.954.262c.513.286.92.737 1.297 1.179c.21.246.413.498.617.75c.5.618 1.005 1.233 1.554 1.809");
}

</style>
