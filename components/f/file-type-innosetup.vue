<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><radialGradient id="SVG0FrvIdqe" cx="16.637" cy="16" r="12.46" gradientUnits="userSpaceOnUse"><stop offset="0" class="q20f7fi2d"/><stop offset=".113" class="fbycxf5_t"/><stop offset=".239" class="gnze4ably"/><stop offset=".339" class="gupmfccva"/><stop offset=".4" class="pzshcshtf"/><stop offset=".473" class="hztqlq69w"/><stop offset=".591" class="qf42oobdj"/><stop offset=".741" class="x7nt4nbis"/><stop offset=".915" class="okb-jnbnx"/><stop offset="1" class="j7ipffbfk"/></radialGradient><linearGradient id="SVGYMFnte3s" x1="20.623" x2="11.589" y1="26.999" y2="11.352" gradientUnits="userSpaceOnUse"><stop offset="0" class="j7ipffbfk"/><stop offset=".78" class="yqs84hbup"/><stop offset=".887" class="pzshcshtf"/><stop offset="1" class="mc4d2-bal"/></linearGradient></defs><path fill="url(#SVG0FrvIdqe)" class="gzyewac4n"/><path class="q96dtfb3h"/><path fill="url(#SVGYMFnte3s)" class="m9gl3-2ty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-innosetup" /></template>
<style>
.fbycxf5_t {
  stop-color: var(--svg-color--afe9fa, #afe9fa);
}

.gnze4ably {
  stop-color: var(--svg-color--87d3f4, #87d3f4);
}

.gupmfccva {
  stop-color: var(--svg-color--6fc6f1, #6fc6f1);
}

.gzyewac4n {
  d: path("M29.1 16A12.46 12.46 0 1 1 16.637 3.54A12.46 12.46 0 0 1 29.1 16");
}

.hztqlq69w {
  stop-color: var(--svg-color--60b9e7, #60b9e7);
}

.j7ipffbfk {
  stop-color: var(--svg-color--003453, #003453);
}

.m9gl3-2ty {
  d: path("M29.518 13.593v6.466l-2.611 2.471v-4.859l-.842.944l-1.34 1.5a23.8 23.8 0 0 1-8.353 5.718a27.2 27.2 0 0 1-6.876 1.9c-.221.021-.693.035-1.232.035a14 14 0 0 1-1.664-.06c-2.016-.4-3.659-1.571-3.9-2.792A5.46 5.46 0 0 1 2.666 22a10.7 10.7 0 0 1 1.359-3.007a23 23 0 0 1 3.559-4.35a28 28 0 0 0-1.3 2.394a10 10 0 0 0-.948 2.873a2.88 2.88 0 0 0 .515 2.31a5.1 5.1 0 0 0 4.278 1.741a20.2 20.2 0 0 0 7.571-1.839a24 24 0 0 0 6.082-3.763l1.4-1.328l.889-.844l-1.226.013l-3.463.036l2.5-2.643h5.641m-20.05-1.019a20.1 20.1 0 0 0-5.85 6.153a11.2 11.2 0 0 0-1.432 3.19a5.9 5.9 0 0 0 .032 3.094c.286 1.418 2.027 2.726 4.284 3.17a14 14 0 0 0 1.757.073c.527 0 1.026-.013 1.278-.037a27.8 27.8 0 0 0 7.019-1.938a24.3 24.3 0 0 0 8.524-5.841l1.34-1.5v4.714L30 20.266v-7.155h-6.33l-3.422 3.618l4.6-.047l-1.4 1.327a23.5 23.5 0 0 1-5.948 3.674a19.8 19.8 0 0 1-7.375 1.8a4.65 4.65 0 0 1-3.89-1.544a2.4 2.4 0 0 1-.426-1.96a9.7 9.7 0 0 1 .906-2.732a39.5 39.5 0 0 1 2.757-4.669Z");
}

.mc4d2-bal {
  stop-color: var(--svg-color--beffff, #beffff);
}

.okb-jnbnx {
  stop-color: var(--svg-color--134e70, #134e70);
}

.pzshcshtf {
  stop-color: var(--svg-color--66c1f0, #66c1f0);
}

.q20f7fi2d {
  stop-color: var(--svg-color--d8ffff, #d8ffff);
}

.q96dtfb3h {
  fill: var(--svg-color--fff, #fff);
  d: path("M23.67 13.111H30v7.155l-3.575 3.383v-4.714l-1.34 1.5a24.3 24.3 0 0 1-8.524 5.841a27.8 27.8 0 0 1-7.019 1.938a21 21 0 0 1-3.035-.036c-2.257-.444-4-1.752-4.284-3.17a5.9 5.9 0 0 1-.032-3.094a11.2 11.2 0 0 1 1.432-3.19a20.1 20.1 0 0 1 5.85-6.153a39.5 39.5 0 0 0-2.757 4.669a9.7 9.7 0 0 0-.906 2.732a2.4 2.4 0 0 0 .426 1.96a4.65 4.65 0 0 0 3.89 1.544a19.8 19.8 0 0 0 7.375-1.8a23.5 23.5 0 0 0 5.949-3.674l1.4-1.327l-4.6.047Z");
}

.qf42oobdj {
  stop-color: var(--svg-color--50a3cf, #50a3cf);
}

.x7nt4nbis {
  stop-color: var(--svg-color--377fa7, #377fa7);
}

.yqs84hbup {
  stop-color: var(--svg-color--0f496a, #0f496a);
}

</style>
