<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":254};
const content = `<defs><linearGradient id="SVG5EyZ2dQp" x1="61.05%" x2="38.45%" y1="82.514%" y2="28.19%"><stop offset="0%" class="l_2jdac5l"/><stop offset="16%" class="uaabk4qua"/><stop offset="43%" class="bitp0urlk"/><stop offset="76%" class="gt1tm40ec"/><stop offset="100%" class="dlc-xtbws"/></linearGradient><linearGradient id="SVGoybLDNXg" x1="62.857%" x2="52.43%" y1="19.708%" y2="78.902%"><stop offset="0%" class="xd4cv6ayz"/><stop offset="11%" class="xd4cv6ayz"/><stop offset="100%" class="ftofrh6wi"/></linearGradient></defs><path fill="url(#SVG5EyZ2dQp)" class="es7tvtbuj"/><path fill="url(#SVGoybLDNXg)" class="d2yv0xb_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:engine-yard-icon" /></template>
<style>
.bitp0urlk {
  stop-color: var(--svg-color--3f5bc2, #3f5bc2);
}

.d2yv0xb_d {
  d: path("m152.457 38.918l-25.965 33.857c29.232.687 52.57 24.581 52.57 53.821s-23.338 53.134-52.57 53.822L93.976 217.37l32.516 35.732c45.254 1.044 87.622-22.156 111.116-60.848c23.495-38.691 24.54-86.984 2.742-126.656S177.228.915 131.97 0h-5.478z");
}

.dlc-xtbws {
  stop-color: var(--svg-color--2f1391, #2f1391);
}

.es7tvtbuj {
  d: path("M72.715 126.611c0-29.75 24.117-53.866 53.866-53.866c29.75 0 53.867 24.117 53.867 53.866c0 29.75-24.117 53.866-53.867 53.866s-53.866-24.116-53.866-53.866m-72.715 0c0 69.893 56.659 126.552 126.552 126.552c69.892 0 126.551-56.66 126.551-126.552S196.444.06 126.552.06C56.7.158.098 56.76 0 126.61");
}

.ftofrh6wi {
  stop-color: var(--svg-color--00bff6, #00bff6);
}

.gt1tm40ec {
  stop-color: var(--svg-color--3633a7, #3633a7);
}

.l_2jdac5l {
  stop-color: var(--svg-color--477cd8, #477cd8);
}

.uaabk4qua {
  stop-color: var(--svg-color--4573d2, #4573d2);
}

.xd4cv6ayz {
  stop-color: var(--svg-color--2055da, #2055da);
}

</style>
