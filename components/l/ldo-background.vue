<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path fill="url(#SVGT3cDMd2U)" class="k246vdb3x"/><path fill="url(#SVGOcWcNdMF)" class="pnvfcdcqh"/><path fill="url(#SVGhqBvVbmz)" class="f38v88btt"/><path fill="url(#SVGS15QccRe)" class="b6435gsih"/></g><defs><linearGradient id="SVGT3cDMd2U" x1="11.998" x2="11.998" y1="4" y2="20.005" gradientUnits="userSpaceOnUse"><stop class="b_fvvlz7a"/><stop offset="1" class="rano1jbzh"/></linearGradient><linearGradient id="SVGOcWcNdMF" x1="11.998" x2="11.998" y1="4.014" y2="19.999" gradientUnits="userSpaceOnUse"><stop class="dtcgcg9vz"/><stop offset=".7" class="w7rj_bcgn"/></linearGradient><linearGradient id="SVGhqBvVbmz" x1="13.179" x2="11" y1="12.895" y2="20.648" gradientUnits="userSpaceOnUse"><stop class="s48hmmbov"/><stop offset=".56" class="n3efd8cmk"/></linearGradient><linearGradient id="SVGS15QccRe" x1="8.917" x2="9.626" y1="8.238" y2="11.661" gradientUnits="userSpaceOnUse"><stop class="mz7dz8bnk"/><stop offset=".61" class="ya1zc1ykq"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ldo-background" /></template>
<style>
.b_fvvlz7a {
  stop-color: var(--svg-color--498be9, #498be9);
}

.b6435gsih {
  d: path("M12.003 4v8.475L8.09 10.173z");
}

.dtcgcg9vz {
  stop-color: var(--svg-color--4a8cea, #4a8cea);
}

.f38v88btt {
  d: path("m12.003 4l3.914 6.177l-3.914 2.298z");
}

.ft5dv1b6b {
  fill: none;
}

.k246vdb3x {
  d: path("m11.998 13.892l-4.54-2.665l-.128.194a5.615 5.615 0 0 0 .753 6.948a5.51 5.51 0 0 0 7.829 0a5.596 5.596 0 0 0 .753-6.948l-.129-.194z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.mz7dz8bnk {
  stop-color: var(--svg-color--ffe235, #ffe235);
}

.n3efd8cmk {
  stop-color: var(--svg-color--568fdd, #568fdd);
}

.pnvfcdcqh {
  d: path("m16.515 11.235l-4.504 2.648l-4.534-2.648l4.534-2.391z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rano1jbzh {
  stop-color: var(--svg-color--56f2ff, #56f2ff);
}

.s48hmmbov {
  stop-color: var(--svg-color--fb8174, #fb8174);
}

.w7rj_bcgn {
  stop-color: var(--svg-color--5abef4, #5abef4);
}

.ya1zc1ykq {
  stop-color: var(--svg-color--5dcba2, #5dcba2);
}

</style>
