<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG0pCRxclF" x1="27.39" x2="5.25" y1="4.62" y2="26.76" gradientUnits="userSpaceOnUse"><stop offset="0" class="l9j_1_tad"/><stop offset="1" class="zzt0f2rvt"/></linearGradient><linearGradient id="SVGPv95KdjN" x1="27.39" x2="5.26" y1="27.39" y2="5.26" gradientUnits="userSpaceOnUse"><stop offset="0" class="cw946-7rp"/><stop offset=".05" class="b-dmo3b1i"/><stop offset=".11" class="vxgakbbra"/><stop offset=".18" class="csu1wnbkn"/><stop offset=".43" class="zfqj0l0cq"/><stop offset=".68" class="ahafflk3h"/><stop offset="1" class="b07o47buw"/></linearGradient><linearGradient id="SVGFADg0cJR" x1="4.67" x2="26.83" y1="27.39" y2="5.25" gradientUnits="userSpaceOnUse"><stop offset="0" class="uze0yccfc"/><stop offset="1" class="b07o47buw"/></linearGradient><linearGradient id="SVGi0k4FdHD" x1="27.39" x2="5.25" y1="4.63" y2="26.76" gradientUnits="userSpaceOnUse"><stop offset="0" class="tq9v7qyki"/><stop offset=".23" class="mtv64p5cy"/><stop offset=".43" class="si415foax"/><stop offset=".61" class="vuod6tfqj"/><stop offset=".77" class="dq5lnrbbp"/><stop offset="1" class="b07o47buw"/></linearGradient></defs><rect id="SVGK7ATMdLf" class="u_-iojbln"/><use fill="url(#SVG0pCRxclF)" href="#SVGK7ATMdLf"/><use fill="url(#SVGPv95KdjN)" href="#SVGK7ATMdLf"/><use fill="url(#SVGFADg0cJR)" href="#SVGK7ATMdLf"/><use fill="url(#SVGi0k4FdHD)" href="#SVGK7ATMdLf"/><path class="n9pqcvbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-asyncapi" /></template>
<style>
.ahafflk3h {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 0.11;
}

.b-dmo3b1i {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 0.84;
}

.b07o47buw {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 0.1;
}

.csu1wnbkn {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 0.51;
}

.cw946-7rp {
  stop-color: var(--svg-color--a829e2, #a829e2);
}

.dq5lnrbbp {
  stop-color: var(--svg-color--993ce5, #993ce5);
  stop-opacity: 0.2;
}

.l9j_1_tad {
  stop-color: var(--svg-color--2dccfd, #2dccfd);
}

.mtv64p5cy {
  stop-color: var(--svg-color--4e9cf4, #4e9cf4);
  stop-opacity: 0.7;
}

.n9pqcvbos {
  fill: var(--svg-color--fff, #fff);
  d: path("m17.6 17.81l-6.51-4.73l-.04-.03l-.83 1.15l6.5 4.72l.04.03zm3.37 1.15l.83-1.15l-6.51-4.72l-.04-.03l-.83 1.15l6.51 4.72zM16.01 7.17c-3.53 0-6.4 2.19-6.4 4.89v.05h1.42v-.05c0-1.91 2.24-3.47 4.98-3.47s4.98 1.56 4.98 3.47v.05h1.42v-.05c-.01-2.7-2.88-4.89-6.41-4.89m4.97 12.78c0 1.91-2.24 3.47-4.98 3.47s-4.98-1.56-4.98-3.47v-.05H9.59v.05c0 2.7 2.87 4.88 6.4 4.88s6.4-2.19 6.4-4.88v-.05h-1.42z");
}

.si415foax {
  stop-color: var(--svg-color--6e73ee, #6e73ee);
  stop-opacity: 0.49;
}

.tq9v7qyki {
  stop-color: var(--svg-color--21d4fd, #21d4fd);
}

.u_-iojbln {
  width: 28px;
  height: 28px;
  x: 2px;
  y: 2px;
  fill: var(--svg-color--000, #000);
  rx: 6.62px;
}

.uze0yccfc {
  stop-color: var(--svg-color--e50e99, #e50e99);
}

.vuod6tfqj {
  stop-color: var(--svg-color--8753e9, #8753e9);
  stop-opacity: 0.32;
}

.vxgakbbra {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 0.67;
}

.zfqj0l0cq {
  stop-color: var(--svg-color--a829e2, #a829e2);
  stop-opacity: 0.2;
}

.zzt0f2rvt {
  stop-color: var(--svg-color--ad20e2, #ad20e2);
}

</style>
