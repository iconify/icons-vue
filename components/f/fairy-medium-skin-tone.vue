<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGidL9AcgO" x1="181.152" x2="210.317" y1="182.727" y2="197.875" gradientTransform="rotate(192.075 137.187 138.735)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGidL9AcgO)" class="y7hp08v5w"/><g class="cnjyhhbwn"><path class="r-o_7kcyf"/><path class="azl6zwbdg"/></g><linearGradient id="SVGNkDDbIve" x1="195.165" x2="238.754" y1="252.46" y2="211.435" gradientTransform="rotate(194.277 141.156 147.884)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGNkDDbIve)" class="pd_bth0yw"/><g class="cnjyhhbwn"><path class="vifvhmb6s"/><path class="vt7pioxhb"/></g><linearGradient id="SVGJ2QUDcHH" x1="1662.647" x2="1691.812" y1="-134.19" y2="-119.042" gradientTransform="rotate(167.925 -830.705 65.384)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGJ2QUDcHH)" class="hby83vbct"/><g class="cnjyhhbwn"><path class="hnzhkj9_i"/><path class="pcrft3yca"/></g><linearGradient id="SVGViDsweYy" x1="1663.963" x2="1707.552" y1="-118.996" y2="-160.022" gradientTransform="rotate(165.723 -834.674 61.03)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="r8ludbcjj"/><stop offset=".156" class="u_ug8ubbn"/><stop offset=".34" class="m5aiqz05p"/><stop offset=".539" class="gsabqfbpm"/><stop offset=".748" class="ltgl6j0rh"/><stop offset=".962" class="sxvxm2bwq"/><stop offset="1" class="awx491bun"/></linearGradient><path fill="url(#SVGViDsweYy)" class="vdjkmvb0a"/><g class="cnjyhhbwn"><path class="rrexejbhj"/><path class="zhitf1lrl"/></g><linearGradient id="SVGnZRo9c1W" x1="46.523" x2="57.631" y1="34.175" y2="34.175" gradientTransform="rotate(185.463 1.619 62.523)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGnZRo9c1W)" class="nebnbfbwy"/><linearGradient id="SVGfchVWcXF" x1="62.482" x2="70.505" y1="38.594" y2="37.827" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="flyfeos6a"/></linearGradient><path fill="url(#SVGfchVWcXF)" class="lmzzrvowm"/><linearGradient id="SVGTXsrjY6S" x1="68.859" x2="67.619" y1="64.867" y2="35.822" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGTXsrjY6S)" class="im0wcqakk"/><linearGradient id="SVGX4HaFebc" x1="59.639" x2="48.639" y1="61.903" y2="9.569" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGX4HaFebc)" class="rlii_hu5p"/><linearGradient id="SVGHiC3EdXn" x1="51.263" x2="19.433" y1="70.105" y2="70.105" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGHiC3EdXn)" class="y3mkxlbwj"/><linearGradient id="SVGiznEKedh" x1="76.658" x2="102.615" y1="74.615" y2="74.615" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGiznEKedh)" class="pksabwa6j"/><linearGradient id="SVGEla4AchP" x1="107.282" x2="99.677" y1="82.707" y2="77.73" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGEla4AchP)" class="pntnc2bla"/><linearGradient id="SVGiHzxVwuT" x1="98.832" x2="102.144" y1="77.973" y2="76.758" gradientTransform="rotate(171.118 1.075 73.16)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset=".437" class="flyfeos6a"/><stop offset="1" class="x16mk-bfp"/></linearGradient><path fill="url(#SVGiHzxVwuT)" class="jdym93bgl"/><path class="sray88kjm"/><path class="vk_0_0bmz"/><path class="qpoil6vnu"/><linearGradient id="SVGVboHfcRK" x1="64" x2="64" y1="100.863" y2="53.246" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="bys3hkbit"/><stop offset=".172" class="z-3wx_xpe"/><stop offset=".408" class="hqeym824h"/><stop offset=".631" class="rn92qobhi"/><stop offset=".835" class="bx20dpxic"/><stop offset="1" class="vy4btutlp"/></linearGradient><path fill="url(#SVGVboHfcRK)" class="cs8erbb5o"/><radialGradient id="SVGZnKWNcwB" cx="63.902" cy="112.285" r="14.124" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tnzyulx-m"/><stop offset="1" class="yac5kp3-q"/></radialGradient><path fill="url(#SVGZnKWNcwB)" class="d8sxed5uy"/><linearGradient id="SVGg1V5PcqE" x1="63.925" x2="63.925" y1="39.409" y2="48.317" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".63" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGg1V5PcqE)" class="k3yiyacql"/><path class="jaoa-pbdf"/><path class="byni-ebdp"/><path class="e_k4js0if"/><g class="h3iawzbwl"><ellipse transform="rotate(-88.802 57.98 24.212)" class="iw0rafbvb"/><ellipse transform="rotate(-88.802 70.055 24.464)" class="gwcidn3kj"/></g><path class="bj_goe9jf"/><path class="ky3yo_oar"/><radialGradient id="SVGoylxSceS" cx="66.049" cy="126.043" r="18.58" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="tnzyulx-m"/><stop offset="1" class="yac5kp3-q"/></radialGradient><path fill="url(#SVGoylxSceS)" class="v_rb6bcwi"/><linearGradient id="SVG5YlLzcZa" x1="104.379" x2="108.704" y1="77.316" y2="77.316" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVG5YlLzcZa)" class="o5v8zkmit"/><linearGradient id="SVG3jsXybOJ" x1="104.379" x2="108.704" y1="79.451" y2="79.451" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVG3jsXybOJ)" class="xp3trfblt"/><linearGradient id="SVGjF8vFbGo" x1="104.379" x2="108.704" y1="81.797" y2="81.797" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGjF8vFbGo)" class="x2fby4bgy"/><linearGradient id="SVG2hIk8Ddh" x1="104.379" x2="108.704" y1="83.785" y2="83.785" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVG2hIk8Ddh)" class="d0jmyfbcv"/><path class="o75gj0slv"/><linearGradient id="SVGQmSepc7n" x1="106.212" x2="100.351" y1="83.832" y2="80.483" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x16mk-bfp"/><stop offset=".575" class="ygm_dez4e"/></linearGradient><path fill="url(#SVGQmSepc7n)" class="sx4o3sb2r"/><path class="fum91pb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:fairy-medium-skin-tone" /></template>
<style>
.awx491bun {
  stop-color: var(--svg-color--ffa6c9, #ffa6c9);
}

.azl6zwbdg {
  d: path("M95.31 80.89c-1.81-6.25-4.28-8.96-6.43-12.49");
}

.bj_goe9jf {
  fill: var(--svg-color--99674f, #99674f);
  d: path("M65.37 27.77a.3.3 0 0 0-.12-.03l-2.6-.05q-.06 0-.12.03c-.24.09-.37.33-.27.59c.11.26.61 1 1.65 1.02s1.58-.7 1.69-.95c.12-.27 0-.51-.23-.61");
}

.bx20dpxic {
  stop-color: var(--svg-color--ff4200, #ff4200);
}

.byni-ebdp {
  fill: var(--svg-color--ba8d68, #ba8d68);
  d: path("M64.39 6.8C58 6.67 51.93 13.38 51.73 23.22c-.21 9.78 5.79 14.75 12 14.88s12.41-4.58 12.62-14.36c.21-9.84-5.57-16.8-11.96-16.94");
}

.bys3hkbit {
  stop-color: var(--svg-color--ffab00, #ffab00);
}

.cnjyhhbwn {
  fill: none;
  stroke: var(--svg-color--87cdde, #87cdde);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-956px, 0.956px);
}

.cs8erbb5o {
  d: path("m76.33 53.51l.14 15.76L68 75.88c-.8.44-1.7.67-2.61.67c-.88.01-1.75-.19-2.54-.58l-11.01-6.48l-.13-15.77l-7.64-6.97s1.05-4.06 8.4-6.3c2.7-.82 6.25-1.4 10.91-1.44c5.15-.04 9.06.59 12 1.51c6.97 2.16 8.55 5.88 8.55 5.88z");
}

.d0jmyfbcv {
  d: path("M103.46 46.8c.15.65.8 1.06 1.45.91l2.68-.62a1.23 1.23 0 0 0 .91-1.46c-.15-.65-.8-1.06-1.45-.91l-2.68.62c-.66.15-1.05.8-.91 1.46");
}

.d8sxed5uy {
  d: path("M77.46 31.58c-.4-.81-.08-1.62 1.18-2.98c1.57-1.68 3.58-6.01 1.53-10.42v-.02h-.41c-.1-.25-.22-.51-.35-.76c-.44-.07-6.88.03-8.5.03H57.02c-1.63 0-8.06-.1-8.5-.03c-.13.25-.25.51-.35.76h-.69c.01.02.02.05.03.07c-1.68 4.3.13 8.54 1.79 10.37c1.05 1.15 1.61 2.06 1.18 3c-.22.47-.55.75-1.03.85l-.83.17l.45.74c.16.27.39.5.64.66c.72.45 1.59.56 2.2.58c.07 0 .17.08.32.26c1.96 2.26 3.5 2.99 8.26 3.17v-.06c1 .04 2.14.06 3.47.06c1.31 0 2.43-.02 3.41-.06v.06c4.81-.18 6.36-.9 8.32-3.17c.15-.17.25-.25.32-.26c.61-.01 1.48-.13 2.2-.58c.26-.16.48-.39.64-.66l.45-.74l-.83-.17c-.43-.1-.77-.38-1.01-.87");
}

.e_k4js0if {
  fill: var(--svg-color--613e31, #613e31);
  d: path("M67.76 21.27c.33-.42 1.09-1.01 2.54-.97c1.44.04 2.17.68 2.47 1.12c.14.19.09.41-.01.54c-.1.12-.37.22-.66.12c-.3-.11-.87-.43-1.84-.46c-.97-.02-1.56.26-1.87.36c-.3.09-.57-.03-.65-.15c-.1-.16-.13-.38.02-.56m-12.2-.33c.33-.42 1.09-1.01 2.54-.97c1.44.04 2.17.68 2.47 1.12c.14.19.09.41-.01.54c-.1.12-.37.22-.66.12c-.3-.11-.87-.43-1.84-.46c-.97-.02-1.56.26-1.87.36c-.3.09-.57-.03-.65-.15a.5.5 0 0 1 .02-.56");
}

.flyfeos6a {
  stop-color: var(--svg-color--ba8d68, #ba8d68);
  stop-opacity: 0;
}

.fum91pb6i {
  fill: var(--svg-color--91674d, #91674d);
  d: path("M100.41 49.91c1.43.24 2.87-.93 3.29-2.32l.04-.13l.02-.07c.01-.03.02-.06 0 0c-.03.07-.11.12-.18.12c-.07.01-.18-.07-.19-.12l.23.47c.16.31.33.61.51.91c.31.56.85 1.36 1.76 1.41c.85.04 1.72-.69 1.57-1.63c-.17-.71-.43-1.37-.83-1.96c-.79-1.17-1.29-2.18-2.9-1.98c1.37.19 1.96 1.03 2.54 2.2c.3.58.53 1.22.65 1.84c.08.47-.49.96-.98.89c-.25-.02-.49-.14-.7-.34c-.21-.19-.36-.47-.54-.76c-.17-.29-.33-.58-.49-.88l-.23-.44c-.04-.12-.23-.26-.39-.25c-.16 0-.32.1-.39.24c-.04.09-.03.11-.04.12l-.01.06l-.03.11c-.17.61-.51 1.16-.96 1.6c-.23.21-.51.39-.8.52c-.32.14-.63.21-.95.39");
}

.gsabqfbpm {
  stop-color: var(--svg-color--abe1e1, #abe1e1);
}

.gwcidn3kj {
  cx: 70.05px;
  cy: 24.46px;
  rx: 1.87px;
  ry: 1.81px;
}

.h3iawzbwl {
  fill: var(--svg-color--49362e, #49362e);
}

.hby83vbct {
  d: path("M24.38 85.2c11.04 11.24 47.55-18.37 39.7-24.6c-9.49-7.54-54.74 9.29-39.7 24.6");
}

.hnzhkj9_i {
  d: path("M25.39 80.43c8.97-10.2 17.84-14.49 30.11-20.32c.28-.13.6-.33.58-.64s-.64-.29-.51-.01M39.54 80.89c3.72-2.49 15.7-13.97 22.79-21.7l-.49.34");
}

.hqeym824h {
  stop-color: var(--svg-color--ff6a00, #ff6a00);
}

.im0wcqakk {
  d: path("m55.64 90.21l13-4.42c0-.43-4.1-11.29-4.1-11.29l8.23-14.6c1.75 3.3 7.11 18.7 8.84 26.71c.65 3.01-.48 6.94-4.98 8.11c-5.02 1.3-9.87 1.92-16.25 2.58c-6.37.66-8.57-5.38-4.74-7.09");
}

.iw0rafbvb {
  cx: 57.98px;
  cy: 24.21px;
  rx: 1.87px;
  ry: 1.81px;
}

.jaoa-pbdf {
  fill: var(--svg-color--99674f, #99674f);
  d: path("m74.12 21.47l-2.71-.06l-14.66-.31l-2.71-.06c-2.16-.05-3.97 1.8-4.02 4.11s1.68 4.23 3.85 4.27l2.71.06l14.66.31l2.71.06c2.16.05 3.97-1.8 4.02-4.11c.05-2.3-1.68-4.22-3.85-4.27");
}

.jdym93bgl {
  d: path("m103.61 47.87l1.04 1.27l-1.12 5.44l-1.14.12l-4.65 4.05l1-8.51s-.28-.06 1.68-.32c1.95-.26 3.19-2.05 3.19-2.05");
}

.k3yiyacql {
  d: path("M68.17 39.18V34.6h-8.68v4.58c-2.81.24-5.12.69-7.01 1.26c.88 3.35 5.03 6.97 11.56 6.92c6.35-.05 10.39-3.56 11.35-6.85c-1.96-.61-4.34-1.09-7.22-1.33");
}

.ky3yo_oar {
  fill: var(--svg-color--5d4037, #5d4037);
  d: path("M67.14 30.77c-1.18.67-5.02.59-6.18-.13c-.66-.41-1.36.18-1.1.8c.26.61 2.33 2.04 4.13 2.08c1.81.04 3.9-1.31 4.19-1.91c.31-.6-.36-1.22-1.04-.84");
}

.lmzzrvowm {
  d: path("m68.64 85.79l-10.37 3.52l1.38 8.02s7.55-.6 11.85-1.51c4.3-.9-2.86-10.03-2.86-10.03");
}

.ltgl6j0rh {
  stop-color: var(--svg-color--ccc9d8, #ccc9d8);
}

.m5aiqz05p {
  stop-color: var(--svg-color--93f1e8, #93f1e8);
}

.nebnbfbwy {
  d: path("M50.58 88.82c-1.64.3-3.18 1.64-3.43 3.29c-.12.82.12 1.64.36 2.43c.65 2.11 1.33 4.2 2.04 6.28c.39 1.14.96 2.43 2.13 2.71c.78.19 1.61-.17 2.18-.74s.92-1.31 1.23-2.05c1.44-3.44 3.12-4.93 3.18-8.65c.07-4.74-4.17-3.91-7.69-3.27");
}

.o5v8zkmit {
  d: path("M104.05 52.19c-.16.66.25 1.33.9 1.48l1.69.41a1.224 1.224 0 1 0 .58-2.38l-1.69-.41a1.21 1.21 0 0 0-1.48.9");
}

.o75gj0slv {
  fill: var(--svg-color--91674d, #91674d);
  d: path("M107.65 51.9c-.46-.34-.96-.47-1.46-.56c-.51-.07-1.02-.09-1.57.08c.46.34.96.48 1.46.56c.51.07 1.02.09 1.57-.08m.19-2.45c-.49-.25-.98-.31-1.47-.31c-.49.01-.98.08-1.46.35c.49.26.98.31 1.47.31c.48-.02.97-.09 1.46-.35m-3.07-1.64c.59.11 1.13.02 1.66-.11c.52-.15 1.03-.35 1.49-.74c-.59-.11-1.13-.03-1.66.11c-.52.15-1.03.35-1.49.74");
}

.pcrft3yca {
  d: path("M31.5 81.54c1.08-3.71 10.56-12.46 12.57-15.75");
}

.pd_bth0yw {
  d: path("M118.54 35.52c6.64 19.8-55.96 37.47-58.55 26.1c-3.57-15.61 50.34-50.56 58.55-26.1");
}

.pksabwa6j {
  d: path("M104.34 49.19c-.08-.09-.17-.17-.26-.26a2.69 2.69 0 0 0-2.8-.48c-1.25.49-5.64 3.46-6.71 4.1l-5.04 3.03l-5.86-9.76l-9.25 4.78l10.65 12.45c1.14 1.71 3.57 2.44 5.39 1.48c0 0 .08-.06.21-.15c.27-.12.54-.28.78-.46c3.08-2.44 9.6-7.91 10.56-8.83c1.49-1.47 4.27-3.79 2.33-5.9");
}

.pntnc2bla {
  d: path("M106.38 53.59c-1.68 1.36-5.35 1.1-6.94-1.5c-2.88-4.72 2.68-7.65 4.84-7.5c2.25.16 5.72 6.17 2.1 9");
}

.qpoil6vnu {
  fill: var(--svg-color--6d4c41, #6d4c41);
  d: path("M104.55 50.74c.22-.05.38-.12.56-.26l-.79 3.89l-1.85.06l.93-4.17c.31.27.67.59 1.15.48");
}

.r-o_7kcyf {
  d: path("M102.66 82.21C94.56 70.73 85.45 65.19 72.5 60.1c-.29-.11-.6-.33-.58-.64s.64-.29.51-.01m20.39 25.21c-2.44-.98-20.06-17.74-27.16-25.47l.49.34");
}

.r8ludbcjj {
  stop-color: var(--svg-color--80ffee, #80ffee);
}

.rlii_hu5p {
  d: path("M65.46 74.38c-.3-4.5-1.21-9.32-2.13-13.95l-.42-.26l-11.06 8.87l-1.49 24.46l-3.22 15.87c-1.56.2-3.17.85-3.78 2.27c-.32.76-.3 1.62-.26 2.45c.1 2.2.23 4.4.4 6.6c.09 1.2.32 2.59 1.38 3.16c.71.38 1.6.24 2.29-.17c.69-.4 1.22-1.04 1.7-1.67c1.47-1.94 3.65-6.32 3.65-6.32s6.21-11.51 8.47-19.36c3.12-10.88 4.32-21.98 4.47-21.95");
}

.rn92qobhi {
  stop-color: var(--svg-color--ff5100, #ff5100);
}

.rrexejbhj {
  d: path("M17.26 29.35c18.27 6.95 32.96 17.46 46.58 31.14M13.11 39.11C28.5 51.57 43.73 56.17 63.01 61.6");
}

.sray88kjm {
  fill: var(--svg-color--6d4c41, #6d4c41);
  stroke: var(--svg-color--6d4c41, #6d4c41);
  stroke-miterlimit: 10;
  d: path("m110.46 21.27l-.09-.03l-9.15 40.97a.482.482 0 1 0 .94.22v-.01z");
}

.sx4o3sb2r {
  d: path("M107.03 48.06c.49.78-.49 1.55-1.08 1.66c-.58.11-1-.38-1.26-.91c-.49-.97-.87-1.39-1.22-1.56c-.32-.16-.03 2.03-2.18 2.48c-1.24.26-2.28-.62-2.29-1.51c-.01-1.19 2.06-3.13 4.71-3.6c2.49.2 3.08 3.06 3.32 3.44");
}

.sxvxm2bwq {
  stop-color: var(--svg-color--f7accb, #f7accb);
}

.tnzyulx-m {
  stop-color: var(--svg-color--ff8f00, #ff8f00);
}

.u_ug8ubbn {
  stop-color: var(--svg-color--85fced, #85fced);
}

.v_rb6bcwi {
  d: path("M79.2 12.11c-2.31-3.95-5.25-3.44-5.36-3.41c.09-1.99-2.5-4.18-4.19-4.81c-.99-.37-1.95-.52-2.85-.52c-3.3 0-5.87 2-6.94 2.42c-1 .4-1.81.55-2.45.55c-2.28 0-2.56-1.94-2.56-1.94c-1.54.92-1.81 2.86-1.15 4.26c0 0-2.31-.68-3.91 1.16s-.75 4.85-.75 4.85s-2.06.5-1.78 3.82c.13 2.12 3.62 3.89 3.62 3.89s.29 2.01 1.17 4.75c.54-2.79 1.61-6.74 1.61-6.74c.03-.01 2.84-.65 5.99-2.65c.66-.42 1.26-.86 1.84-1.3c1.38-1.03 2.69-2 4.52-2.46c.53-.13 1.03-.2 1.5-.2c2.06 0 3.18 1.3 3.61 2.25h.08c1.09 0 3.74.5 4.64 5.13c.3 1.56.45 4.1.24 6.37c3.19-2.62 3.83-7.75 3.83-7.75c.83-3.66-.2-6.81-.71-7.67");
}

.vdjkmvb0a {
  d: path("M9.47 33.3C2.82 53.1 65.42 70.78 68.02 59.4C71.58 43.8 17.67 8.84 9.47 33.3");
}

.vifvhmb6s {
  d: path("M110.46 31.56C92.2 38.51 77.77 49.02 64.15 62.7m51.62-25.23c-15.38 12.46-31.5 20.92-50.79 26.35");
}

.vk_0_0bmz {
  fill: var(--svg-color--ffd600, #ffd600);
  d: path("m111.39 14.69l-2.5 3.44l-4.24-.11l2.5 3.44l-1.41 4.01l4.04-1.32l3.37 2.58v-4.25l3.5-2.41l-4.05-1.31z");
}

.vt7pioxhb {
  d: path("M97.43 31.02c-5.33 4.8-7.72 8.38-10.12 12.42m26.43-10.18c-4.72 3.95-8.3 7.58-10.26 13.35m-12.06 6.76c-5.97 1.22-10.36 1.32-15.62-.61");
}

.vy4btutlp {
  stop-color: var(--svg-color--ff3d00, #ff3d00);
}

.x16mk-bfp {
  stop-color: var(--svg-color--a47b62, #a47b62);
}

.x2fby4bgy {
  d: path("M103.98 48.17s.55 1.3 1.21 1.3l2.52-.01c.67-.01 1.21-.55 1.2-1.22v-.1c0-.67-.55-1.21-1.22-1.2l-2.52.01c-.66.01-1.2.55-1.19 1.22");
}

.xp3trfblt {
  d: path("M104.14 50.31c-.07.68.43 1.28 1.11 1.35l2.26.23c.68.07 1.28-.43 1.35-1.11s-.43-1.28-1.11-1.35l-2.26-.23c-.68-.06-1.28.43-1.35 1.11");
}

.y3mkxlbwj {
  d: path("M30.01 75.09c-2.86-.68-5.05-1.69-6.54-2.19c-1.5-.5-1.55-3.35 1.59-2.43c1.79.52 1.08-.68-.39-1.45c-1.47-.78-5.2 1.08-6.08.25c-.61-.57-.52-1.39-.18-1.7c1.15-1.02 3.9-1.99 6.32-1.88c2.16.1 5.55 3.29 7.63 2.74c.01 0 3.97-7.04 7.59-13.47l5.86-10.41l10.88 4.62s-18.5 21.87-19.47 22.77c-2.17 2.01-4.17 3.87-7.21 3.15");
}

.y7hp08v5w {
  d: path("M103.62 85.2c-11.04 11.24-47.55-18.37-39.7-24.6c9.49-7.54 54.74 9.29 39.7 24.6");
}

.yac5kp3-q {
  stop-color: var(--svg-color--d32f2f, #d32f2f);
}

.ygm_dez4e {
  stop-color: var(--svg-color--ba8d68, #ba8d68);
}

.z-3wx_xpe {
  stop-color: var(--svg-color--ff8d00, #ff8d00);
}

.zhitf1lrl {
  d: path("M29.36 29.5c4.23 2.82 6.09 4.91 7.84 9.61m-20.43-5.36c4.72 3.95 7.3 8.23 9.26 14m4.91-5.03c7.32 3.4 16.19 9.65 21.26 9.82");
}

</style>
