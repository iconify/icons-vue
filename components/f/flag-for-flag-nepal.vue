<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="r3xp6emih"/><path class="upopxcbze"/><path class="vvr32tbah"/><path class="hgo-8hb1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-nepal" /></template>
<style>
.hgo-8hb1f {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.6 21.8c.3-.5.4-1.2.4-1.8c0-2.2-1.8-4-4-4s-4 1.8-4 4c0 .7.2 1.3.4 1.8C10.5 21 9 20 9 20s1.5 6 7 6c5.6 0 7-6 7-6s-1.5 1-3.4 1.8M16 39.6l1.6-1.6l.6 2.2l2.2-.6l-.6 2.2l2.2.6l-1.6 1.6l1.6 1.6l-2.2.6l.6 2.2l-2.2-.6l-.6 2.2l-1.6-1.6l-1.6 1.6l-.6-2.2l-2.2.6l.6-2.2l-2.2-.6l1.6-1.6l-1.6-1.6l2.2-.6l-.6-2.2l2.2.6l.6-2.2z");
}

.r3xp6emih {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M44.5 56.5L20 32h24L18.7 6.7h-2.8A29.87 29.87 0 0 0 2 32c0 16.6 13.4 30 30 30c4.4 0 8.7-1 12.5-2.7z");
}

.upopxcbze {
  fill: var(--svg-color--f9f9f9, #f9f9f9);
  d: path("M32 2c-4.4 0-8.7 1-12.5 2.7v4.8l21 21h-21v3.2l23.6 23.6h5C56.5 52 62 42.6 62 32C62 15.4 48.6 2 32 2");
}

.vvr32tbah {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M19.5 4.7c-1.3.6-2.5 1.2-3.7 2L39.2 30h-24l29.3 29.3c1.3-.6 2.5-1.2 3.7-2L24.8 34h24z");
}

</style>
