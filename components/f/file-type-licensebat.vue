<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGZCjvRcJv" x1="2.591" x2="29.409" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop offset="0" class="c-_gqkbqx"/><stop offset=".014" class="mnqfvhbhx"/><stop offset=".238" class="sway81bbk"/><stop offset=".471" class="emelnpr2g"/><stop offset=".717" class="t91mpe8mt"/><stop offset=".999" class="e95cr_bth"/></linearGradient><linearGradient id="SVG024scefm" x1="19.532" x2="11.214" y1="27.942" y2="16.674" href="#SVGZCjvRcJv"/></defs><path fill="url(#SVGZCjvRcJv)" class="uir_1yd1v"/><path fill="url(#SVG024scefm)" class="a1gwtcfgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-licensebat" /></template>
<style>
.a1gwtcfgo {
  d: path("M24.1 23.839a5.287 5.287 0 0 1-5-7.011a2.1 2.1 0 0 1-1.6.688a2.15 2.15 0 0 1-1.417-.507c-.026.023-.054-.065-.082-.044c-.028-.021-.056.067-.082.044a2.15 2.15 0 0 1-1.417.507a2.1 2.1 0 0 1-1.6-.688a5.287 5.287 0 0 1-7.595 6.329a13.33 13.33 0 0 0 10.664 5.315h.054a13.33 13.33 0 0 0 10.664-5.315a5.26 5.26 0 0 1-2.589.682");
}

.c-_gqkbqx {
  stop-color: var(--svg-color--ffca3f, #ffca3f);
}

.e95cr_bth {
  stop-color: var(--svg-color--d38f29, #d38f29);
}

.emelnpr2g {
  stop-color: var(--svg-color--de9d2e, #de9d2e);
}

.mnqfvhbhx {
  stop-color: var(--svg-color--fec83e, #fec83e);
}

.sway81bbk {
  stop-color: var(--svg-color--ebaf35, #ebaf35);
}

.t91mpe8mt {
  stop-color: var(--svg-color--d6922a, #d6922a);
}

.uir_1yd1v {
  d: path("m22.652 3.474l-3.994 4.348l-.055.055l-.6.656a7.2 7.2 0 1 1-4.006 0l-.6-.656l-.055-.055l-3.994-4.348a13.409 13.409 0 1 0 13.3 0Z");
}

</style>
