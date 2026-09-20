<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGc46FhddW)" class="r4i437pya"/><path clip-rule="evenodd" class="a_qcezg4a"/><path class="xp9dwgbuq"/></g><defs><linearGradient id="SVGc46FhddW" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="l52_756ao"/><stop offset="1" class="z94d75b3w"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bcmc-background" /></template>
<style>
.a_qcezg4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.059a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.l52_756ao {
  stop-color: var(--svg-color--fcab2f, #fcab2f);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xp9dwgbuq {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 7.294H9.177V12l.94-.471V8.235H12a1.412 1.412 0 0 1 .626 2.678c-2.588 1.284-5.238 2.494-7.845 3.755l.414.847l7.12-3.464s1.106-.47 1.422-.818A2.344 2.344 0 0 0 12 7.293m7.633 2.748l-.414-.847l-4.913 2.56a1.883 1.883 0 0 1-.894 3.539h-3.294v-1.567l-.941.48v2.028h4.235a2.822 2.822 0 0 0 2.39-4.33z");
}

.z94d75b3w {
  stop-color: var(--svg-color--e45e0e, #e45e0e);
}

</style>
