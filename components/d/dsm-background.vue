<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGpmkLAd0I)" class="r4i437pya"/><path class="pectpdbqu"/><path class="epar_2b-j"/><path class="pr6-jqb1l"/></g><defs><linearGradient id="SVGpmkLAd0I" x1="4.751" x2="19.25" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="mvmwefbik"/><stop offset="1" class="xup29chwy"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dsm-background" /></template>
<style>
.epar_2b-j {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.775 5.32c.375-.25.76-.32 1.1-.32c2.095 0 4.425 1.105 6.23 2.63c1.794 1.515 3.144 3.52 3.144 5.38c0 1.88-1.45 3.51-3.184 4.639c-1.75 1.14-3.885 1.85-5.455 1.85a3.27 3.27 0 0 1-1.985-.605c-.504-.388-.9-.9-1.15-1.485c-.53-1.15-.65-2.56-.65-3.645c0-3.75.385-5.92.95-7.164a2.94 2.94 0 0 1 1-1.28m-.45 1.525c-.515 1.12-.985 3.185-.985 6.92c0 1.06.2 2.364.675 3.399c.208.52.539.982.965 1.345c.415.3.94.49 1.63.49c1.425 0 3.45-.75 5.13-1.845c1.684-1.1 2.99-2.57 2.99-4.15c0-1.6-1.27-3.45-3.015-4.924C13.98 6.615 11.78 5.5 9.88 5.5c-.255 0-.515.05-.77.22a2.8 2.8 0 0 0-.785 1.125");
}

.ft5dv1b6b {
  fill: none;
}

.mvmwefbik {
  stop-color: var(--svg-color--fe723f, #fe723f);
}

.pectpdbqu {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.74 4.32c.375-.25.76-.32 1.1-.32c2.09 0 4.425 1.105 6.23 2.63c1.794 1.515 3.144 3.52 3.144 5.38c0 1.88-1.45 3.509-3.184 4.639c-1.75 1.14-3.89 1.85-5.455 1.85a3.27 3.27 0 0 1-1.985-.605c-.504-.388-.9-.9-1.15-1.485c-.53-1.15-.65-2.56-.65-3.645c0-3.75.385-5.92.95-7.164a2.94 2.94 0 0 1 1-1.28m-.45 1.525c-.515 1.12-.985 3.185-.985 6.92c0 1.06.2 2.364.675 3.4c.208.52.539.98.965 1.344c.41.3.94.49 1.63.49c1.42 0 3.45-.75 5.125-1.845c1.69-1.1 3-2.57 3-4.15c0-1.6-1.276-3.45-3.02-4.924c-1.73-1.465-3.94-2.58-5.83-2.58c-.255 0-.515.05-.77.22a2.8 2.8 0 0 0-.785 1.125z");
}

.pr6-jqb1l {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.705 5.82c.375-.25.76-.32 1.1-.32c2.09 0 4.425 1.105 6.23 2.63c1.795 1.515 3.144 3.52 3.144 5.38c0 1.88-1.45 3.509-3.184 4.639c-1.75 1.14-3.89 1.85-5.455 1.85a3.27 3.27 0 0 1-1.985-.605A3.7 3.7 0 0 1 5.4 17.909c-.525-1.15-.65-2.56-.65-3.645c0-3.75.39-5.92.955-7.164a2.94 2.94 0 0 1 1-1.28m-.45 1.525c-.515 1.12-.985 3.185-.985 6.92c0 1.06.2 2.364.675 3.399c.208.52.539.982.965 1.345c.41.3.94.49 1.63.49c1.42 0 3.45-.75 5.125-1.845c1.685-1.1 3-2.57 3-4.15c0-1.6-1.275-3.45-3.02-4.924C11.91 7.115 9.705 6 7.805 6c-.25 0-.515.05-.765.22a2.8 2.8 0 0 0-.79 1.13z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xup29chwy {
  stop-color: var(--svg-color--fca553, #fca553);
}

</style>
