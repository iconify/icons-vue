<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tl3tdac8p"/><path class="c-m0vcc3k"/><path class="pp9urmbsf"/><circle class="i4a5_qbra"/><path class="x3krmbc6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-new-caledonia" /></template>
<style>
.c-m0vcc3k {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M32 2C18.9 2 7.8 10.4 3.7 22h56.6C56.2 10.4 45.1 2 32 2");
}

.i4a5_qbra {
  cx: 24px;
  cy: 32px;
  r: 17.7px;
  fill: var(--svg-color--ffe62e, #ffe62e);
}

.pp9urmbsf {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M60.3 42c1.1-3.1 1.7-6.5 1.7-10s-.6-6.9-1.7-10H3.7C2.6 25.1 2 28.5 2 32s.6 6.9 1.7 10z");
}

.tl3tdac8p {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M32 62c13.1 0 24.2-8.3 28.3-20H3.7C7.8 53.7 18.9 62 32 62");
}

.x3krmbc6n {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M24 14c-9.9 0-18 8.1-18 18s8.1 18 18 18s18-8.1 18-18s-8.1-18-18-18M6.6 32c0-9.5 7.6-17.2 17-17.4v3.9c-1.1.5-1.9.9-2.1 1.9c0 .1-.1 1.4-.1 1.8c0 0 .2 0 .6-.3c.2-.2.8-.3 1.6-.7v2c-1.2.2-2 1.2-2 2.4s.9 2.2 2 2.4v.5c-.9 0-1.7-.3-2.4-1.7c-.4-.8-1.4-2-1.4-2s.5 1.3.5 2.7c.1 2 1.9 2.2 3.2 2.2v.4H21v.7h2.6v.4c-1.2.1-2 .7-2 1.5s.9 1.4 2 1.5v.4H21v.4h2.6v.4c-2 .1-3 .9-3.1 2.1c-.2 2.5-.7 4.5-.7 4.5s.8-.9 1.6-3.1c.4-1 1.3-1.6 2.2-1.8v.3c-.9.2-1.6 1.4-1.6 2.8s.7 2.6 1.6 2.8v.8c-1.2 0-2.4.3-3 .8c-.8.7-2.8 2.6-3.6 3.4c-6.1-2.7-10.4-8.8-10.4-16m24 16.1c-.7-.8-2.5-2.7-3.6-3.5c-.6-.5-1.6-.7-2.6-.8V43c.9-.2 1.6-1.4 1.6-2.8s-.7-2.6-1.6-2.8v-.3c.9.1 1.8.8 2.2 1.8c.9 2.2 1.6 3.1 1.6 3.1s-.5-2-.7-4.5c-.1-1.2-1.1-2-3.1-2.1V35H27v-.7h-2.6v-.4c1.2-.1 2-.7 2-1.5s-.9-1.4-2-1.5v-.4H27v-.7h-2.6v-.4c1.4 0 3.1-.2 3.2-2.2c.1-1.4.5-2.7.5-2.7s-1 1.2-1.4 2c-.7 1.4-1.5 1.7-2.4 1.7v-.5c1.2-.2 2-1.2 2-2.4s-.9-2.2-2-2.4v-2.5c.7-.6 1.5-1.5 2.3-2.9c.4-.8.2-1.1.2-1.1s0 .1-.3.3c-.7.6-1.5 1-2.2 1.4v-3.5c9.4.2 17 7.9 17 17.4c.1 7.3-4.4 13.5-10.7 16.1");
}

</style>
