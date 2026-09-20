<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGC6GMyenn)" clip-rule="evenodd" class="q3l30gbpo"/><path class="rzq7u_zph"/><defs><linearGradient id="SVGC6GMyenn" x1="4" x2="21.817" y1="3" y2="18.442" gradientUnits="userSpaceOnUse"><stop class="jpk0-gmbu"/><stop offset=".5" class="tpj1u91vs"/><stop offset="1" class="jdfs-hrsg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gunz" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jdfs-hrsg {
  stop-color: var(--svg-color--d3f1fb, #d3f1fb);
}

.jpk0-gmbu {
  stop-color: var(--svg-color--c2fccd, #c2fccd);
}

.q3l30gbpo {
  fill-rule: evenodd;
  d: path("M17.725 3v4.927L19.6 9.802v10.25a.947.947 0 0 1-.947.948h-1.81l-.392-.393h-2.668l-.392.393H9.32L4 15.679V3zm1.525 17.041a.607.607 0 1 1-1.214 0a.607.607 0 0 1 1.214 0");
}

.rzq7u_zph {
  fill: var(--svg-color--000, #000);
  d: path("M16.845 6.637h-8.44v7.217l1.634 1.632h2.939l-3.69-3.69v-.853h2.572L9.287 8.371V7.52h4.133l3.425 3.424v.882h-2.543l2.543 2.544v3.874H7.811l-2.93-2.93V3.88h11.964zm2.057 13.624q-.003-.02-.003-.04l-.001-.032a.2.2 0 0 0-.007-.045a.13.13 0 0 0-.04-.073a.1.1 0 0 0-.04-.02a.15.15 0 0 0 .072-.06a.2.2 0 0 0 .021-.09a.2.2 0 0 0-.012-.064a.17.17 0 0 0-.162-.1h-.317v.592h.13v-.231h.13q.049 0 .071.022t.029.068q.005.035.006.074a.2.2 0 0 0 .014.067h.13a.1.1 0 0 1-.013-.03zm-.15-.276q-.022.02-.066.02h-.143v-.165h.143q.044 0 .066.019q.022.02.022.062q0 .044-.022.066z");
}

.tpj1u91vs {
  stop-color: var(--svg-color--abf4e4, #abf4e4);
}

</style>
