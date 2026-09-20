<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGVpl6kc7N)" class="c1g39myfd"/><defs><linearGradient id="SVGVpl6kc7N" x1="17.205" x2="4.754" y1="6.729" y2="13.961" gradientUnits="userSpaceOnUse"><stop class="vpesd2iao"/><stop offset="1" class="ybqdvudrq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dfyn" /></template>
<style>
.c1g39myfd {
  d: path("M10.55 13.286H5.314L7.886 3h4.145c2.077 0 3.461 1.882 3.625 3.62c.129 1.39-.54 3.328-.89 4.094h3.92L8.642 21z");
}

.ft5dv1b6b {
  fill: none;
}

.vpesd2iao {
  stop-color: var(--svg-color--b8566f, #b8566f);
}

.ybqdvudrq {
  stop-color: var(--svg-color--60b9e2, #60b9e2);
}

</style>
