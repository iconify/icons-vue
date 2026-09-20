<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rm692-b5x"/><path class="fljz5bcur"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bico" /></template>
<style>
.fljz5bcur {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.933 10a5.51 5.51 0 0 1-4.266 2h-2V4.493C9.667 3.12 8.407 2 7 2C5.587 2 4.334 3.12 4.334 4.493V22h8.94c.446 0 .866-.04 1.28-.133a6.29 6.29 0 0 0 5.113-6.114A6.45 6.45 0 0 0 15.933 10");
}

.ft5dv1b6b {
  fill: none;
}

.rm692-b5x {
  fill: var(--svg-color--d85111, #D85111);
  d: path("M14.447 2.667A5.2 5.2 0 0 0 11.887 2H6.893a2.52 2.52 0 0 1 2.554 2.494V12h2.44a5.15 5.15 0 0 0 4.006-1.906a4.932 4.932 0 0 0-1.446-7.42z");
}

</style>
