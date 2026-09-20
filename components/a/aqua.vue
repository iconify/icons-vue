<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGh0z6Kj1Q)" class="vb7n012lj"/><defs><linearGradient id="SVGh0z6Kj1Q" x1="7.219" x2="16.5" y1="4.969" y2="19.313" gradientUnits="userSpaceOnUse"><stop class="o5llwfbye"/><stop offset=".2" class="aharzcc7u"/><stop offset=".43" class="rhehpzbxm"/><stop offset="1" class="hlk5xo3gn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aqua" /></template>
<style>
.aharzcc7u {
  stop-color: var(--svg-color--4377ec, #4377ec);
}

.ft5dv1b6b {
  fill: none;
}

.hlk5xo3gn {
  stop-color: var(--svg-color--1f123e, #1f123e);
}

.o5llwfbye {
  stop-color: var(--svg-color--55b6ff, #55b6ff);
}

.rhehpzbxm {
  stop-color: var(--svg-color--2b2cae, #2b2cae);
}

.vb7n012lj {
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

</style>
