<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG3hDnJcpR)" class="btuxg9orh"/><path fill="url(#SVGKxQyKb6C)" class="ar59v0bug"/><path fill="url(#SVGZaEsicMN)" class="ggzwpdcoo"/><path fill="url(#SVG4l1JpbtZ)" class="bca79clut"/><defs><linearGradient id="SVG3hDnJcpR" x1="5.185" x2="13.942" y1="6.649" y2="20.893" gradientUnits="userSpaceOnUse"><stop class="hfnudub7s"/><stop offset="1" class="vcu82t1si"/></linearGradient><linearGradient id="SVGKxQyKb6C" x1="4.176" x2="20.637" y1="11.519" y2="11.519" gradientUnits="userSpaceOnUse"><stop class="bedks9bcb"/><stop offset="1" class="ea4nk4mug"/></linearGradient><linearGradient id="SVGZaEsicMN" x1="11.999" x2="11.999" y1="5.994" y2="18.005" gradientUnits="userSpaceOnUse"><stop class="hhkmj6wsj"/><stop offset="1" class="r3sxrzbzm"/></linearGradient><linearGradient id="SVG4l1JpbtZ" x1="19.005" x2="19.005" y1="6" y2="18.001" gradientUnits="userSpaceOnUse"><stop class="z6w9qrbsm"/><stop offset="1" class="ea4nk4mug"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ait" /></template>
<style>
.ar59v0bug {
  d: path("M12.215 15.5h-5.5c-.166.08-.52.25-.566.285c-.04.035-.335 1.49-.475 2.215h7.49c.186 0 .3-.205.21-.37z");
}

.bca79clut {
  d: path("M21 17.261c0 .41-.325.74-.725.74H17.03c.665 0 .91-.6.97-.9V6.571c0-.316.29-.576.6-.576h1.835A.57.57 0 0 1 21 6.57z");
}

.bedks9bcb {
  stop-color: var(--svg-color--134491, #134491);
}

.btuxg9orh {
  d: path("M10.3 6.584A1.58 1.58 0 0 0 9.35 6h3.654c.585 0 .97.55 1.09.82L18 13.95v3.126c-.085.615-.47.93-.905.93c-.35 0-.875-.575-1-.86L11.049 7.51l-.745-.925z");
}

.ea4nk4mug {
  stop-color: var(--svg-color--00adf0, #00adf0);
}

.ft5dv1b6b {
  fill: none;
}

.ggzwpdcoo {
  d: path("M6.784 15.58c-.95 1.83.84 2.41.885 2.42H4.314C2.8 18 2.9 16.78 3.14 16.17c1.585-2.996 4.78-9.05 4.89-9.306C8.164 6.544 8.55 6 9.2 6c.52 0 .88.285.99.425l.85 1.075c-1.1 2.085-3.5 6.616-4.255 8.08");
}

.hfnudub7s {
  stop-color: var(--svg-color--06a9ee, #06a9ee);
}

.hhkmj6wsj {
  stop-color: var(--svg-color--0458a0, #0458a0);
}

.r3sxrzbzm {
  stop-color: var(--svg-color--00ace8, #00ace8);
}

.vcu82t1si {
  stop-color: var(--svg-color--00529b, #00529b);
}

.z6w9qrbsm {
  stop-color: var(--svg-color--05599f, #05599f);
}

</style>
