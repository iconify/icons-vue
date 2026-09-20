<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBTvNkeML)" class="r4i437pya"/><path class="uvyo57bie"/></g><defs><linearGradient id="SVGBTvNkeML" x1="7.812" x2="18.815" y1="5.714" y2="18.746" gradientUnits="userSpaceOnUse"><stop class="s4mwgqfbm"/><stop offset="1" class="od8p9tb1w"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ens-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.od8p9tb1w {
  stop-color: var(--svg-color--53b1ef, #53b1ef);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.s4mwgqfbm {
  stop-color: var(--svg-color--7c97fa, #7c97fa);
}

.uvyo57bie {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.711 10.471c.16.342.547 1.009.547 1.009L11.747 4L7.369 7.084a1.9 1.9 0 0 0-.622.69a3.22 3.22 0 0 0-.031 2.697zm-1.773 2.462a5.07 5.07 0 0 0 1.955 3.663L11.743 20s-3.027-4.4-5.583-8.787a4.5 4.5 0 0 1-.515-1.493a2.4 2.4 0 0 1 0-.716l-.196.378a5.8 5.8 0 0 0-.52 1.69c-.053.621-.044 1.244.013 1.866zm12.351.596a18 18 0 0 0-.547-1.009L12.258 20l4.378-3.08c.258-.178.47-.413.622-.693a3.22 3.22 0 0 0 .027-2.698zm1.773-2.462a5.07 5.07 0 0 0-1.955-3.663L12.257 4s3.028 4.4 5.583 8.787c.258.462.431.969.511 1.493c.036.236.036.48 0 .716l.196-.378a5.8 5.8 0 0 0 .524-1.69c.054-.621.045-1.244-.013-1.866z");
}

</style>
