<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG0TyNuc3B)" clip-rule="evenodd" class="mw9npkkup"/><path fill="url(#SVG4NIRoegG)" class="j95qqcc5q"/><path fill="url(#SVGzmIjScNf)" clip-rule="evenodd" class="etumq7bdy"/><path fill="url(#SVG2WJFVdPo)" class="n73vk9_8o"/><defs><linearGradient id="SVG0TyNuc3B" x1="5.732" x2="17.946" y1="6.215" y2="17.625" gradientUnits="userSpaceOnUse"><stop class="phbljubkl"/><stop offset="1" class="qs1d5vblb"/></linearGradient><linearGradient id="SVG4NIRoegG" x1="5.732" x2="17.945" y1="6.214" y2="17.624" gradientUnits="userSpaceOnUse"><stop class="phbljubkl"/><stop offset="1" class="qs1d5vblb"/></linearGradient><linearGradient id="SVGzmIjScNf" x1="5.733" x2="17.946" y1="6.214" y2="17.624" gradientUnits="userSpaceOnUse"><stop class="phbljubkl"/><stop offset="1" class="qs1d5vblb"/></linearGradient><linearGradient id="SVG2WJFVdPo" x1="5.733" x2="17.946" y1="6.214" y2="17.625" gradientUnits="userSpaceOnUse"><stop class="phbljubkl"/><stop offset="1" class="qs1d5vblb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:doga" /></template>
<style>
.etumq7bdy {
  fill-rule: evenodd;
  d: path("M13.862 3H6.724v14.275h7.138a7.137 7.137 0 1 0 0-14.275m0 1.862H8.587v10.551h5.275a5.276 5.276 0 0 0 0-10.551");
}

.ft5dv1b6b {
  fill: none;
}

.j95qqcc5q {
  d: path("m16.952 15.99l-2.333.664a6 6 0 0 1-.342.478l1.223 1.434a7.05 7.05 0 0 0 1.452-2.576");
}

.mw9npkkup {
  fill-rule: evenodd;
  d: path("M10.138 6.725H3V21h7.138a7.136 7.136 0 0 0 5.047-12.185a7.14 7.14 0 0 0-5.047-2.09m0 1.862H4.862v10.551h5.276a5.276 5.276 0 0 0 0-10.551");
}

.n73vk9_8o {
  d: path("M8.587 10.448L6.724 8.586h1.863z");
}

.phbljubkl {
  stop-color: var(--svg-color--422c81, #422c81);
}

.qs1d5vblb {
  stop-color: var(--svg-color--7b368a, #7b368a);
}

</style>
