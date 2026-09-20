<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGacRydb1V)" class="x4gbnkbgi"/><path fill="url(#SVGfiSPCceh)" class="as-hknbct"/><path class="a_p5tqu2q"/></g><defs><linearGradient id="SVGacRydb1V" x1="16.391" x2="7.491" y1="5" y2="18.857" gradientUnits="userSpaceOnUse"><stop offset=".16" class="xzkl2dbcs"/><stop offset=".59" class="z3ptbacko"/><stop offset="1" class="p_c3p5pmw"/></linearGradient><linearGradient id="SVGfiSPCceh" x1="14.353" x2="12.293" y1="4.5" y2="7.892" gradientUnits="userSpaceOnUse"><stop offset=".07" class="oar3xy26p"/><stop offset="1" class="sivdrfbzo"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kzen-background" /></template>
<style>
.a_p5tqu2q {
  fill: var(--svg-color--181b1e, #181b1e);
  d: path("M10.588 7.294H12v8.941h-1.412zm6.019-2.353l-.833-.875L15.722 4a12.93 12.93 0 0 0-2.781 7.962c0 3.05 1.059 5.85 2.823 8.038l.942-.932a11.6 11.6 0 0 1-2.396-7.106c0-2.626.852-5.091 2.297-7.02");
}

.as-hknbct {
  d: path("M19.53 12a7.53 7.53 0 1 0-15.06 0a7.53 7.53 0 0 0 15.06 0");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.oar3xy26p {
  stop-color: var(--svg-color--ff5353, #ff5353);
}

.p_c3p5pmw {
  stop-color: var(--svg-color--c50101, #c50101);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sivdrfbzo {
  stop-color: var(--svg-color--c50101, #c50101);
  stop-opacity: 0;
}

.x4gbnkbgi {
  d: path("M12 19.53a7.53 7.53 0 1 0 0-15.06a7.53 7.53 0 0 0 0 15.06");
}

.xzkl2dbcs {
  stop-color: var(--svg-color--ffa3a3, #ffa3a3);
}

.z3ptbacko {
  stop-color: var(--svg-color--c50000, #c50000);
}

</style>
