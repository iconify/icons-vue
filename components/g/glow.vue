<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGzCGGbequ)" class="wbzd4bbcq"/><defs><linearGradient id="SVGzCGGbequ" x1="3.009" x2="20.985" y1="2.964" y2="21.009" gradientUnits="userSpaceOnUse"><stop class="qaja-xbzz"/><stop offset="1" class="xnf3oubdt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:glow" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.qaja-xbzz {
  stop-color: var(--svg-color--6f03fb, #6f03fb);
}

.wbzd4bbcq {
  d: path("M18.312 18.416A8.97 8.97 0 0 1 12 21a8.97 8.97 0 0 1-6.3-2.574c3.685-2.903 8.923-2.906 12.612-.01m.104-.104A8.97 8.97 0 0 0 21 12a8.97 8.97 0 0 0-2.572-6.3c-2.905 3.697-2.908 8.923-.012 12.612m-.09-12.714c-3.695 2.91-8.95 2.906-12.64-.011A8.97 8.97 0 0 1 12 3c2.465 0 4.7.992 6.325 2.598m-12.74.087A8.97 8.97 0 0 0 3 12c0 2.466.992 4.7 2.598 6.325c2.91-3.694 2.906-8.948-.011-12.64");
}

.xnf3oubdt {
  stop-color: var(--svg-color--ec5eff, #ec5eff);
}

</style>
