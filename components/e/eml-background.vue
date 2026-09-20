<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGm0bQpbBG)" class="r4i437pya"/><path class="se2x5ldlb"/><path class="x2jx9vc0s"/></g><defs><linearGradient id="SVGm0bQpbBG" x1="6.573" x2="15.023" y1="7.999" y2="17.234" gradientUnits="userSpaceOnUse"><stop class="d45rsrbzp"/><stop offset="1" class="o_w89tbpe"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:eml-background" /></template>
<style>
.d45rsrbzp {
  stop-color: var(--svg-color--6db82b, #6db82b);
}

.ft5dv1b6b {
  fill: none;
}

.o_w89tbpe {
  stop-color: var(--svg-color--c9d808, #c9d808);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.se2x5ldlb {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 13.822a3.955 3.955 0 0 1-4-3.91A3.956 3.956 0 0 1 8 6a3.99 3.99 0 0 1 3.822 2.756c.431 1.364.711 1.68.178 4.026c0 1.044.089 2 .267 2.609c-.534-.52-.96-1.822-1.6-1.822c-.903 0-1.778.257-2.667.257z");
}

.x2jx9vc0s {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.751 10.37c-.71.066-1.426.057-1.684-.196c-.427-.418-1.067-1.218-1.334-1.565c.178.436.534 1.462.534 2.089c0 .249-.08.631-.178 1.071C11.525 14.445 12.382 18 16 18c2.209 0 4-1.75 4-3.91a3.953 3.953 0 0 0-4-3.912c-.435 0-.858.067-1.249.191");
}

</style>
