<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGbdMipwwy)" class="r4i437pya"/><path class="eob_sbc3f"/></g><defs><linearGradient id="SVGbdMipwwy" x1="18.35" x2="6.424" y1="9.072" y2="15.899" gradientUnits="userSpaceOnUse"><stop class="ci5uumcxf"/><stop offset="1" class="slh9t21xx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:imtoken-background" /></template>
<style>
.ci5uumcxf {
  stop-color: var(--svg-color--0cc5ff, #0cc5ff);
}

.eob_sbc3f {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.958 6.784c.528 7.08-4.066 10.428-8.184 10.785c-3.829.332-7.433-2-7.75-5.581c-.26-2.96 1.586-4.219 3.036-4.344c1.491-.13 2.745.89 2.854 2.123c.104 1.187-.643 1.726-1.162 1.771c-.411.036-.928-.211-.975-.742c-.04-.456.135-.518.092-1.002c-.076-.863-.835-.963-1.25-.928c-.504.044-1.416.626-1.288 2.074c.129 1.462 1.543 2.616 3.397 2.456c2-.174 3.393-1.717 3.497-3.881q0-.174.072-.333V9.18a1 1 0 0 1 .076-.13q.063-.096.168-.21q.001-.004.002-.003q.077-.086.183-.186c.874-.817 4.021-2.744 6.998-2.134a.3.3 0 0 1 .234.267");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.slh9t21xx {
  stop-color: var(--svg-color--007fff, #007fff);
}

</style>
