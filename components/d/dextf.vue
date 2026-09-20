<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGXkDAxdDE)" class="retug7whi"/><defs><linearGradient id="SVGXkDAxdDE" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="kgvvfobkb"/><stop offset=".83" class="q0ld9ljem"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dextf" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.kgvvfobkb {
  stop-color: var(--svg-color--72f64b, #72f64b);
}

.q0ld9ljem {
  stop-color: var(--svg-color--2d6a1c, #2d6a1c);
}

.retug7whi {
  d: path("M3 18.876V5.124C3 3.948 3.96 3 5.16 3h6.702C16.902 3 21 7.032 21 12s-4.092 9-9.138 9H5.154A2.134 2.134 0 0 1 3 18.876m1.524-5.562l2.928.636L13.8 8.748v8.19l2.4 2.052V6.36l-1.614-.882l-10.062 7.83z");
}

</style>
