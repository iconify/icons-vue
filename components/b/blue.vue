<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGdOaAUbmt)" clip-rule="evenodd" class="k2vwnfn1n"/><path fill="url(#SVG01erJdcP)" clip-rule="evenodd" class="gfcf7j9ey"/><path fill="url(#SVGvURXbcps)" clip-rule="evenodd" class="qnxvumq2o"/><defs><linearGradient id="SVGdOaAUbmt" x1="903" x2="903" y1="53.433" y2="1779.92" gradientUnits="userSpaceOnUse"><stop class="he9fa_pkm"/><stop offset="1" class="f-kr6z77o"/></linearGradient><linearGradient id="SVG01erJdcP" x1="903" x2="903" y1="7.154" y2="1317.29" gradientUnits="userSpaceOnUse"><stop class="m8llqqb3s"/><stop offset="1" class="xxmqfqauw"/></linearGradient><linearGradient id="SVGvURXbcps" x1="903" x2="903" y1="37.324" y2="957.69" gradientUnits="userSpaceOnUse"><stop class="aphfj3b8a"/><stop offset="1" class="t9y8jcbfy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:blue" /></template>
<style>
.aphfj3b8a {
  stop-color: var(--svg-color--8bd7f9, #8bd7f9);
}

.f-kr6z77o {
  stop-color: var(--svg-color--0c2550, #0c2550);
}

.ft5dv1b6b {
  fill: none;
}

.gfcf7j9ey {
  fill-rule: evenodd;
  d: path("M8.298 7.154h7.404c1.842 0 2.51.19 3.184.545a3.73 3.73 0 0 1 1.562 1.542c.36.665.552 1.324.552 3.143v2.924c0 1.819-.192 2.478-.552 3.143a3.73 3.73 0 0 1-1.562 1.542c-.674.356-1.342.545-3.184.545H8.298c-1.842 0-2.51-.189-3.184-.545a3.73 3.73 0 0 1-1.562-1.542C3.192 17.786 3 17.127 3 15.308v-2.924c0-1.819.192-2.478.552-3.143a3.73 3.73 0 0 1 1.562-1.542c.674-.356 1.342-.545 3.184-.545");
}

.he9fa_pkm {
  stop-color: var(--svg-color--174697, #174697);
}

.k2vwnfn1n {
  fill-rule: evenodd;
  d: path("M8.298 3h7.404c1.842 0 2.51.19 3.184.545a3.73 3.73 0 0 1 1.562 1.542c.36.665.552 1.325.552 3.143v7.309c0 1.819-.192 2.478-.552 3.143a3.73 3.73 0 0 1-1.562 1.542c-.674.356-1.342.545-3.184.545H8.298c-1.842 0-2.51-.19-3.184-.545a3.73 3.73 0 0 1-1.562-1.542C3.192 18.017 3 17.358 3 15.539V8.23c0-1.818.192-2.478.552-3.143a3.73 3.73 0 0 1 1.562-1.542C5.788 3.189 6.456 3 8.298 3");
}

.m8llqqb3s {
  stop-color: var(--svg-color--3f78dc, #3f78dc);
}

.qnxvumq2o {
  fill-rule: evenodd;
  d: path("M7.212 11.539h9.576c1.234 0 1.853.16 2.423.46c.57.302 1.017.743 1.322 1.306c.305.562.467 1.174.467 2.392v1.145c0 1.218-.162 1.83-.467 2.392a3.16 3.16 0 0 1-1.322 1.305c-.57.3-1.19.461-2.423.461H7.212c-1.234 0-1.853-.16-2.423-.461a3.16 3.16 0 0 1-1.322-1.305C3.162 18.671 3 18.06 3 16.842v-1.145c0-1.218.162-1.83.467-2.392A3.16 3.16 0 0 1 4.79 12c.57-.301 1.19-.461 2.423-.461");
}

.t9y8jcbfy {
  stop-color: var(--svg-color--68bbe1, #68bbe1);
}

.xxmqfqauw {
  stop-color: var(--svg-color--2f5fb3, #2f5fb3);
}

</style>
