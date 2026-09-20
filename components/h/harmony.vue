<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG3peijcDH)" class="g_k7d86ff"/><defs><linearGradient id="SVG3peijcDH" x1="4.14" x2="19.757" y1="19.638" y2="3.978" gradientUnits="userSpaceOnUse"><stop class="tzi0cjbjn"/><stop offset="1" class="m4k59qb9b"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:harmony" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g_k7d86ff {
  d: path("M17.117 3.025a3.88 3.88 0 0 0-3.884 3.87v4.293q-.598.042-1.233.044c-.424 0-.831.017-1.233.04V6.897a3.884 3.884 0 0 0-7.767 0v10.258a3.884 3.884 0 0 0 7.767 0v-4.292q.598-.042 1.233-.044c.424 0 .831-.017 1.233-.041v4.377a3.884 3.884 0 0 0 7.767 0V6.896a3.88 3.88 0 0 0-3.883-3.871M6.883 4.61a2.29 2.29 0 0 1 2.292 2.285v4.545a13 13 0 0 0-3.3.933c-.457.2-.887.457-1.28.764V6.896A2.29 2.29 0 0 1 6.883 4.61m2.292 12.543a2.292 2.292 0 0 1-4.584 0v-1.03c0-.908.72-1.77 1.927-2.305c.85-.367 1.743-.628 2.657-.777zm7.942 2.285a2.29 2.29 0 0 1-2.292-2.285v-4.545a13 13 0 0 0 3.3-.933c.457-.2.887-.457 1.28-.764v6.242a2.29 2.29 0 0 1-2.288 2.285m.365-9.214c-.85.367-1.743.627-2.657.777V6.896a2.292 2.292 0 0 1 4.584 0v1.029c0 .905-.72 1.766-1.927 2.3");
}

.m4k59qb9b {
  stop-color: var(--svg-color--69fabd, #69fabd);
}

.tzi0cjbjn {
  stop-color: var(--svg-color--00aee9, #00aee9);
}

</style>
