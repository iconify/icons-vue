<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG0zBkneNn)" clip-rule="evenodd" class="er_sa6b0a"/><path fill="url(#SVGHTrqpdsH)" class="gqlga-6np"/><path fill="url(#SVGq1wTbhib)" class="ryfjvdoyv"/><defs><linearGradient id="SVG0zBkneNn" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="ugdas1_pi"/><stop offset=".409" class="e888s1bvb"/><stop offset=".757" class="ql8bzolen"/><stop offset="1" class="vt01peelf"/></linearGradient><linearGradient id="SVGHTrqpdsH" x1="12.001" x2="12.001" y1="2.999" y2="20.999" gradientUnits="userSpaceOnUse"><stop class="ugdas1_pi"/><stop offset=".409" class="e888s1bvb"/><stop offset=".757" class="ql8bzolen"/><stop offset="1" class="vt01peelf"/></linearGradient><linearGradient id="SVGq1wTbhib" x1="12.001" x2="12.001" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="ugdas1_pi"/><stop offset=".409" class="e888s1bvb"/><stop offset=".757" class="ql8bzolen"/><stop offset="1" class="vt01peelf"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ecoin" /></template>
<style>
.e888s1bvb {
  stop-color: var(--svg-color--f9da3b, #f9da3b);
}

.er_sa6b0a {
  fill-rule: evenodd;
  d: path("M12 20.437a8.438 8.438 0 1 0 0-16.875a8.438 8.438 0 0 0 0 16.875M12 21a9 9 0 0 0 9-9a9 9 0 0 0-9-9a9 9 0 0 0-9 9a9 9 0 0 0 9 9");
}

.ft5dv1b6b {
  fill: none;
}

.gqlga-6np {
  d: path("M11.92 4.69c-2.403 0-3.752 1.046-4.15 1.301l2.623 1.179c.665-.195 1.571-.226 1.94-.218c3.948.256 4.769 3.87 4.686 5.61H8.487c.473 2.26 1.91 2.812 3.66 2.812c1.52 0 2.671-1.176 2.671-1.687h1.778c-.696 2.456-2.733 3.388-4.263 3.388a6.8 6.8 0 0 1-1.94-.268l-2.635 1.2c1.504 1.134 3.677 1.343 4.575 1.305c5.18 0 6.98-4.655 6.98-7.19c0-5.838-4.8-7.433-7.393-7.433");
}

.ql8bzolen {
  stop-color: var(--svg-color--edc62d, #edc62d);
}

.ryfjvdoyv {
  d: path("M12.141 8.625c-2.253 0-3.283 1.86-3.515 2.813h6.75c-.14-.923-1.253-2.813-3.235-2.813");
}

.ugdas1_pi {
  stop-color: var(--svg-color--cdae26, #cdae26);
}

.vt01peelf {
  stop-color: var(--svg-color--ceaf26, #ceaf26);
}

</style>
