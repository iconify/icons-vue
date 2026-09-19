<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="xnsv5gbgl"/><path class="vubdscbal"/><path class="r66uli3dk"/><g class="hxik4rbqd"><path class="w8w2y4prq"/><circle class="aom7hvbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-philippines" /></template>
<style>
.aom7hvbij {
  cx: 15.7px;
  cy: 32px;
  r: 4.5px;
}

.hxik4rbqd {
  fill: var(--svg-color--ffce31, #ffce31);
}

.r66uli3dk {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M11.3 10.3C5.6 15.8 2 23.5 2 32s3.6 16.2 9.3 21.7L33 32z");
}

.vubdscbal {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M62 32C62 15.4 48.6 2 32 2c-8 0-15.3 3.2-20.7 8.3L33 32z");
}

.w8w2y4prq {
  d: path("m13 13.6l-.8 1.4l1.1 1.1l-1.5-.2l-.8 1.4l-.2-1.5l-1.5-.2l1.4-.8l-.2-1.5l1.1 1.1zm.2 34.4l-1.1 1.2l.8 1.3l-1.4-.6l-1.1 1.2l.2-1.6l-1.5-.6l1.6-.3l.2-1.6l.8 1.4zm17.3-16l-1.5.5V34l-1-1.2l-1.5.4l1-1.2l-1-1.2l1.5.4l1-1.2v1.5zm-6.8-1.5l-.6-.5l-6.5 1.4h.1l6.1-1.6l-.8-.5l-5.2 2l4.3-3.6l-.1-.9l-4.5 4.6h-.1l4.5-5l-.1-.7l-.7.1l-4 5.2v-.1l3.7-5.3l-.9.1l-2.7 4.9l1-5.6l-.6-.6l-.6 6.5v.1l.2-6.8l-.5-.5l-.5.5l.2 6.8v-.1l-.5-6.4l-.6.6l1 5.6l-2.7-4.9l-.9-.1l3.7 5.3v.1l-4.1-5.4l-.7-.1l-.1.7l4.5 5h-.1l-4.5-4.6l-.1.9l4.3 3.6l-5.2-2l-.7.5l6.1 1.6h.1L8.3 30l-.6.4l.4.6l6.6.9h-.1l-6.3-.6l.5.7l5.6-.1L9.2 34l-.2.9l5.7-2.8h.1l-5.9 3.2l-.2.7l.7.2l5.7-3.6v.1l-5.2 3.7l.8.2l4.2-3.7l-2.9 4.9l.4.8l2.6-5.8l.1-.1l-2.5 6.3l.3.7l.7-.3l2.1-6.5v.1L14 39.2l.8-.4l.9-5.6l.9 5.6l.8.4l-1.7-6.2v-.1l2.1 6.5l.7.3l.3-.7l-2.5-6.3l.1.1l2.6 5.8l.4-.8l-2.8-4.9l4.2 3.7l.8-.2l-5.2-3.7v-.1l5.7 3.6l.7-.2l-.2-.7l-5.9-3.2h.1l5.7 2.8l-.3-.9l-5.3-1.9l5.6.1l.5-.7l-6.3.6h-.1l6.6-.9zm-7.2 1.6");
}

.xnsv5gbgl {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M33 32L11.3 53.7C16.7 58.8 24 62 32 62c16.6 0 30-13.4 30-30z");
}

</style>
