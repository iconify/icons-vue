<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGagdSNbya)" class="r4i437pya"/><path class="jouc9db6v"/></g><defs><linearGradient id="SVGagdSNbya" x1="7.604" x2="24.256" y1="6.775" y2="23.511" gradientUnits="userSpaceOnUse"><stop class="iec-__bqf"/><stop offset="1" class="p1we3jffn"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iec-__bqf {
  stop-color: var(--svg-color--1a1e21, #1a1e21);
}

.jouc9db6v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.637 13.007c-.458.569-1.422.985-2.137.985c-.687 0-1.5-.355-1.5-1.186c0-.791.658-1.075 1.322-1.21c.783-.163 1.95-.26 2.678-.612c0 .661.058 1.453-.363 2.023M12 6.56c1.257 0 2 .391 2 1.285c0 .983-1.481 1.009-2.185 1.059c-1.536.197-2.724.337-3.506.533c-.811.168-1.448.392-1.883.729c-.921.593-1.42 1.73-1.42 2.802c-.058.981.29 1.822 1.015 2.495c.723.7 1.824 1.037 3.36 1.037c.927 0 1.71-.14 2.433-.392a6.9 6.9 0 0 0 1.97-1.206L14 16.5h5c-.435-.308-.5-1.289-.5-1.822V8.652C18.5 5.039 15.652 4 12.25 4c-2.887 0-6.483.641-6.75 4H10c.075-.937.743-1.44 2-1.44m6.5 11.94h-13V20h13z");
}

.p1we3jffn {
  stop-color: var(--svg-color--06060a, #06060a);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
