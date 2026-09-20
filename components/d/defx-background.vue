<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGHxmN26CN)" class="r4i437pya"/><path class="uwulnlb7a"/></g><defs><linearGradient id="SVGHxmN26CN" x1="20.028" x2="4" y1="12.02" y2="12.02" gradientUnits="userSpaceOnUse"><stop class="lb7utqbjl"/><stop offset="1" class="ikxc1zjjo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:defx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ikxc1zjjo {
  stop-color: var(--svg-color--4ba69b, #4ba69b);
}

.lb7utqbjl {
  stop-color: var(--svg-color--2d73ba, #2d73ba);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uwulnlb7a {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.2 7.2l3.74 2.28l3.908-2.28L20 9.588v4.852l-4.148 2.36l-3.916-2.152L8.2 16.8L4 14.44V9.588zm7.2 8.568v-3.5L8.6 8.272v3.476zm-7.6-4.024V8.24l-3 1.772v3.58zm-2.6 2.48L8.224 16l2.976-1.784l-3-1.816zm11-1.964v3.496l3-1.736v-3.58zm2.6-2.46L15.848 8L12.8 9.8l3.048 1.732z");
}

</style>
