<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGOFmwMdLk)" class="oo3utnpqr"/><path fill="url(#SVGI0x3Xc0S)" class="x-nzhgb6j"/><path class="i3vtrkb7p"/><path class="pq9_77obl"/><path class="pnxaaibtt"/><path class="yi63fqpys"/><defs><linearGradient id="SVGOFmwMdLk" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="axqkeqbej"/><stop offset="1" class="ei0zymyrv"/></linearGradient><linearGradient id="SVGI0x3Xc0S" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="kh06k_b0k"/><stop offset="1" class="aeuhgn_-f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lm" /></template>
<style>
.aeuhgn_-f {
  stop-color: var(--svg-color--015429, #015429);
}

.axqkeqbej {
  stop-color: var(--svg-color--1e5ea8, #1e5ea8);
}

.ei0zymyrv {
  stop-color: var(--svg-color--163f71, #163f71);
}

.ft5dv1b6b {
  fill: none;
}

.i3vtrkb7p {
  fill: var(--svg-color--004f9f, #004f9f);
  d: path("M7.263 9.158L4.421 7.737L12.001 3l7.104 4.263l-2.842 1.421L12 6.316z");
}

.kh06k_b0k {
  stop-color: var(--svg-color--03783c, #03783c);
}

.oo3utnpqr {
  d: path("m4.421 7.737l2.842 1.421v5.21L4.421 15.79z");
}

.pnxaaibtt {
  fill: var(--svg-color--0174bc, #0174bc);
  d: path("M15.316 9.63H8.684L12 11.763z");
}

.pq9_77obl {
  fill: var(--svg-color--009945, #009945);
  d: path("m16.737 14.842l2.842 1.42L11.999 21l-7.104-4.263l2.842-1.421L12 17.684z");
}

.x-nzhgb6j {
  d: path("m19.579 8.21l-2.842 1.422v5.21l2.842 1.422z");
}

.yi63fqpys {
  fill: var(--svg-color--024531, #024531);
  d: path("M12 15.789v-4.027l3.316-2.131z");
}

</style>
