<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGLHpFKe9B)" clip-rule="evenodd" class="h26zjj1zg"/><path fill="url(#SVGfp7Cpbsg)" clip-rule="evenodd" class="o1o2g0bgt"/><path fill="url(#SVG3rph2cNp)" clip-rule="evenodd" class="fjntyzb8p"/><defs><linearGradient id="SVGLHpFKe9B" x1="4.895" x2="20.037" y1="7.413" y2="16.519" gradientUnits="userSpaceOnUse"><stop class="tq_dn5-le"/><stop offset=".42" class="v4an1_12a"/><stop offset="1" class="sfv4578gy"/></linearGradient><linearGradient id="SVGfp7Cpbsg" x1="3.474" x2="21" y1="14.085" y2="14.085" gradientUnits="userSpaceOnUse"><stop class="d8l0vibnd"/><stop offset=".47" class="l0zmwcwjn"/><stop offset="1" class="o9_wa1biy"/></linearGradient><linearGradient id="SVG3rph2cNp" x1="12.001" x2="12.001" y1="10.541" y2="20.757" gradientUnits="userSpaceOnUse"><stop class="ts7oncbse"/><stop offset=".41" class="crpxa3bel"/><stop offset="1" class="xv7urve6j"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apfc" /></template>
<style>
.crpxa3bel {
  stop-color: var(--svg-color--b4b4b4, #b4b4b4);
}

.d8l0vibnd {
  stop-color: var(--svg-color--e1b88a, #e1b88a);
}

.fjntyzb8p {
  fill-rule: evenodd;
  d: path("m12 10.541l4.622 2.55v5.117L12 20.758l-4.621-2.55V13.09zm-4.135 7.38l3.892 2.15v-4.52l-3.892-1.93zm4.378-2.364v4.514l3.892-2.15v-4.296zm3.615-2.335L12 15.138l-3.858-1.916L12 11.096z");
}

.ft5dv1b6b {
  fill: none;
}

.h26zjj1zg {
  fill-rule: evenodd;
  d: path("m7.622 3.243l4.621 2.55v5.117l-4.621 2.55L3 10.91V5.792zm-4.135 7.38l3.891 2.15v-4.52l-3.891-1.93zm4.378-2.364v4.514l3.892-2.15V6.327zm3.614-2.336L7.623 7.84L3.764 5.923l3.858-2.125z");
}

.l0zmwcwjn {
  stop-color: var(--svg-color--274527, #274527);
}

.o1o2g0bgt {
  fill-rule: evenodd;
  d: path("M16.378 3.243L21 5.793v5.117l-4.622 2.55l-4.621-2.55V5.792zm-4.135 7.38l3.892 2.15v-4.52l-3.892-1.93zm4.379-2.364v4.514l3.891-2.15V6.327zm3.614-2.336L16.378 7.84L12.52 5.923l3.858-2.125z");
}

.o9_wa1biy {
  stop-color: var(--svg-color--3a5959, #3a5959);
}

.sfv4578gy {
  stop-color: var(--svg-color--d6b087, #d6b087);
}

.tq_dn5-le {
  stop-color: var(--svg-color--c66329, #c66329);
}

.ts7oncbse {
  stop-color: var(--svg-color--d3b088, #d3b088);
}

.v4an1_12a {
  stop-color: var(--svg-color--e08d39, #e08d39);
}

.xv7urve6j {
  stop-color: var(--svg-color--a3a2a4, #a3a2a4);
}

</style>
