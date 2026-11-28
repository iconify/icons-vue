<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(1.03 1.03)scale(.93589)"><ellipse class="dh1m9-b8y"/><path class="no78sbb9q"/><path class="izov_v4bj"/><path class="b3x4az5so"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-watchmanconfig" /></template>
<style>
.b3x4az5so {
  fill: var(--svg-color--4356e6, #4356e6);
  d: path("M7.96 16c2.9 2.84 5.64 5.22 8.04 5.1c2.4.12 5.14-2.26 8.04-5.1c-2.9-2.84-5.64-5.22-8.04-5.1c-2.4-.12-5.14 2.26-8.04 5.1m8.6-4l2.5 1.5a1.1 1.1 0 0 1 .56 1v3a1.2 1.2 0 0 1-.55 1L16.55 20a1.1 1.1 0 0 1-1.1 0l-2.52-1.5a1.1 1.1 0 0 1-.55-1v-3a1.2 1.2 0 0 1 .55-1l2.52-1.5a1.1 1.1 0 0 1 1.1 0");
}

.dh1m9-b8y {
  cx: 16px;
  cy: 16px;
  fill: var(--svg-color--fff, #fff);
  rx: 14.44px;
  ry: 14.93px;
}

.izov_v4bj {
  fill: var(--svg-color--4356e6, #4356e6);
  d: path("M14.04 14.17a1.1 1.1 0 0 0-.55 1v1.67a1.2 1.2 0 0 0 .55 1l1.4.84a1.1 1.1 0 0 0 1.11 0l1.41-.84a1.1 1.1 0 0 0 .55-1v-1.68a1.2 1.2 0 0 0-.55-.99l-1.4-.84a1.1 1.1 0 0 0-1.11 0Z");
}

.no78sbb9q {
  fill: var(--svg-color--4356e6, #4356e6);
  d: path("m4.71 17.65l.02-.01l.01-.02l.97-.96l.65-.65l-.65-.65l-.97-.97l-.01-.01l-.02-.01l-.93-1l-1.59-1.72a15.5 15.5 0 0 0 0 8.73l1.59-1.71q.46-.52.93-1.02m25.1-6.01l-1.59 1.71l-.93 1l-.02.01l-.01.02l-.97.96l-.65.65l.65.65l.97.97l.01.01l.02.01l.93 1l1.59 1.72a15.4 15.4 0 0 0 0-8.71m-4.97 5.15c-3.02 2.97-5.9 5.46-8.67 5.46h-.34c-2.77 0-5.65-2.5-8.67-5.46l-1.65 1.65c-.98 1.06-1.98 2.11-2.9 3.14A14.5 14.5 0 0 0 16 30.93a14.5 14.5 0 0 0 13.4-9.35q-1.41-1.55-2.91-3.14zM7.15 15.21c3.02-2.97 5.9-5.46 8.67-5.46h.34c2.77 0 5.65 2.5 8.67 5.46l1.65-1.65c.98-1.06 1.98-2.11 2.9-3.14A14.5 14.5 0 0 0 16 1.07a14.5 14.5 0 0 0-13.4 9.35c.93 1.03 1.93 2.08 2.91 3.14z");
}

</style>
