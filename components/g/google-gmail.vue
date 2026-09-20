<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":204};
const content = `<defs><linearGradient id="SVGHzDbHcwG" x1="165" x2="165" y1="44" y2="166" gradientUnits="userSpaceOnUse"><stop class="yhn04vbkr"/><stop offset=".17" class="dt0nt770y"/><stop offset=".39" class="vtv1nccpp"/><stop offset=".62" class="wl9cflb0o"/><stop offset=".86" class="iohm7z9kg"/><stop offset="1" class="h_b_e_04y"/></linearGradient><linearGradient id="SVG41ATXboZ" x1="8" x2="184" y1="46.13" y2="46.13" gradientUnits="userSpaceOnUse"><stop offset=".08" class="t826k_ytv"/><stop offset=".3" class="py37ihbjc"/><stop offset=".5" class="py37ihbjc"/><stop offset=".65" class="py37ihbjc"/><stop offset=".72" class="vbc46g07o"/><stop offset=".86" class="j12rx_w5u"/><stop offset=".91" class="s5swet9dp"/><stop offset=".96" class="nkxpenbar"/></linearGradient></defs><path fill="url(#SVGHzDbHcwG)" transform="translate(-11.636 -37.818)scale(1.45454)" class="eajv9dbuu"/><path class="c0bgxvbsg"/><path fill="url(#SVG41ATXboZ)" transform="translate(-11.636 -37.818)scale(1.45454)" class="zmtkg03ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-gmail" /></template>
<style>
.c0bgxvbsg {
  fill: var(--svg-color--fc413d, #fc413d);
  d: path("M55.273 26.182H0v160c0 9.638 7.816 17.454 17.455 17.454h29.09a8.727 8.727 0 0 0 8.728-8.728z");
}

.dt0nt770y {
  stop-color: var(--svg-color--42c868, #42c868);
}

.eajv9dbuu {
  d: path("M146 44h38v110c0 6.627-5.373 12-12 12h-20a6 6 0 0 1-6-6z");
}

.h_b_e_04y {
  stop-color: var(--svg-color--3186ff, #3186ff);
}

.iohm7z9kg {
  stop-color: var(--svg-color--3c90ff, #3c90ff);
}

.j12rx_w5u {
  stop-color: var(--svg-color--feb10c, #feb10c);
}

.nkxpenbar {
  stop-color: var(--svg-color--ffdb0f, #ffdb0f);
}

.py37ihbjc {
  stop-color: var(--svg-color--fc413d, #fc413d);
}

.s5swet9dp {
  stop-color: var(--svg-color--fec700, #fec700);
}

.t826k_ytv {
  stop-color: var(--svg-color--ff63a0, #ff63a0);
}

.vbc46g07o {
  stop-color: var(--svg-color--fc5c30, #fc5c30);
}

.vtv1nccpp {
  stop-color: var(--svg-color--0ebc5f, #0ebc5f);
}

.wl9cflb0o {
  stop-color: var(--svg-color--00a9bb, #00a9bb);
}

.yhn04vbkr {
  stop-color: var(--svg-color--60d673, #60d673);
}

.zmtkg03ek {
  d: path("M39.226 30.456c-8.033-6.752-20.018-5.714-26.77 2.319c-6.752 8.032-5.714 20.017 2.319 26.77l76.078 63.949a8 8 0 0 0 10.295 0l76.078-63.95c8.032-6.752 9.07-18.737 2.318-26.77c-6.752-8.032-18.737-9.07-26.769-2.318L96 78.18z");
}

</style>
