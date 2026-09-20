<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="kzd8ssbjj"/><path fill="url(#SVGBfYKqdbs)" class="mhco16b6m"/><path class="oadevh2wf"/></g><defs><linearGradient id="SVGBfYKqdbs" x1="22.815" x2="22.453" y1="7.036" y2="17.651" gradientUnits="userSpaceOnUse"><stop class="lgq976b8j"/><stop offset=".17" class="fmfw85b0z"/><stop offset=".24" class="fmfw85b0z"/><stop offset=".32" class="lgq976b8j"/><stop offset=".42" class="fmfw85b0z"/><stop offset=".58" class="fmfw85b0z"/><stop offset=".67" class="lgq976b8j"/><stop offset=".76" class="fmfw85b0z"/><stop offset=".84" class="fmfw85b0z"/><stop offset="1" class="lgq976b8j"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:epik-background" /></template>
<style>
.fmfw85b0z {
  stop-color: var(--svg-color--fefcff, #fefcff);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.kzd8ssbjj {
  fill: var(--svg-color--683ca4, #683ca4);
  fill-rule: evenodd;
  d: path("M12 20a7.998 7.998 0 0 0 7.391-11.061A8 8 0 0 0 12 4a8 8 0 0 0 0 16m0-.889a7.112 7.112 0 1 0 0-14.223a7.112 7.112 0 0 0 0 14.223");
}

.lgq976b8j {
  stop-color: var(--svg-color--fefcff, #fefcff);
}

.mhco16b6m {
  d: path("M11.555 7.325c0-.364.293-.658.653-.658h.68v9.791a.874.874 0 0 1-.876.876h-.457z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.oadevh2wf {
  fill: var(--svg-color--fefcff, #fefcff);
  d: path("M14.222 11.307h-.152c-2.115 0-4.084 0-4.084-1.378c0-1.528 3.244-1.257 4.56-.622c.249.12.6.098.773-.12l.356-.444a.204.204 0 0 0-.058-.311a7.6 7.6 0 0 0-3.484-.876c-2.151 0-3.974 1-3.974 2.378c0 1.053 1.111 1.636 1.743 1.822h-.01c-.644.165-2.097.96-2.097 2.125c0 1.457 1.933 2.564 4.209 2.564c1.618 0 3.186-.613 3.858-.987a.223.223 0 0 0 .062-.333l-.37-.467c-.186-.23-.56-.253-.826-.124c-1.386.666-4.88.973-4.88-.653c0-1.44 1.925-1.436 4.12-1.436h.254z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
