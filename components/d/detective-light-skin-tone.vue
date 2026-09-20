<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b-xyrbc2z"/><radialGradient id="SVGa3nmpdIE" cx="91.724" cy="50.373" r="6.921" gradientTransform="rotate(154.924 85.064 58.476)scale(1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="fwx9zn6gv"/><stop offset="1" class="x21lzsbti"/></radialGradient><path fill="url(#SVGa3nmpdIE)" class="hm99f6b5d"/><radialGradient id="SVGVqiyncTb" cx="110.25" cy="67.052" r="30.399" gradientTransform="matrix(-.0746 -.9972 .8311 -.0622 22.543 174.955)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGVqiyncTb)" class="mb-144bpe"/><radialGradient id="SVGR9IpPede" cx="32.563" cy="69.445" r="30.399" gradientTransform="matrix(.0746 -.9972 -.8311 -.0622 85.926 97.633)" gradientUnits="userSpaceOnUse"><stop offset=".725" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGR9IpPede)" class="bcon_cs6f"/><radialGradient id="SVGd0jgVcjw" cx="12.375" cy="49.23" r="6.921" gradientTransform="rotate(205.076 5.046 55.68)scale(-1 .7418)" gradientUnits="userSpaceOnUse"><stop offset=".663" class="fwx9zn6gv"/><stop offset="1" class="x21lzsbti"/></radialGradient><path fill="url(#SVGd0jgVcjw)" class="g8wv28bsg"/><linearGradient id="SVGGmd5jeGi" x1="53" x2="53" y1="34.74" y2="-4.33" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="vnlt8_bly"/><stop offset=".288" class="vnlt8_bly"/><stop offset=".449" class="ixuczfbhb"/><stop offset=".684" class="xn5dksb-u"/><stop offset=".962" class="sozvcjboj"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGGmd5jeGi)" class="pl8-kjvjg"/><path class="yfzjuybrm"/><path class="v--k8egri"/><path class="kszhj0bry"/><path class="ves7lbs2g"/><ellipse class="fk7-i2x1l"/><path class="v17w-n78o"/><circle class="ndz8cojbi"/><g class="xv67-cbxy"><circle class="hq1vc1g6j"/><circle class="ho7jlzxwz"/></g><path class="jxlhhchve"/><circle class="yizguit1x"/><g class="xv67-cbxy"><circle class="vtk1xpb3x"/><circle class="fbu7rg8-d"/></g><linearGradient id="SVGdm1OgkkY" x1="33.95" x2="33.95" y1="-1252.802" y2="-1294.034" gradientTransform="matrix(1 0 0 -1 0 -1158)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="vlzxxcccm"/><stop offset=".3" class="u_6s-xoka"/><stop offset=".502" class="cvjflgbcp"/><stop offset=".718" class="d5o-7dbzj"/><stop offset=".942" class="fos5e643c"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGdm1OgkkY)" class="b9vy7ub3a"/><linearGradient id="SVGdV6kEc0g" x1="66.05" x2="66.05" y1="-1252.775" y2="-1294.034" gradientTransform="matrix(1 0 0 -1 0 -1158)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="vlzxxcccm"/><stop offset=".3" class="u_6s-xoka"/><stop offset=".502" class="cvjflgbcp"/><stop offset=".718" class="d5o-7dbzj"/><stop offset=".942" class="fos5e643c"/><stop offset="1" class="wk_lp_wlk"/></linearGradient><path fill="url(#SVGdV6kEc0g)" class="ugadeyb1e"/><path class="itte6eubh"/><path class="p6dl0tbxz"/><g class="edr3jwbtv"><ellipse class="wp5yo6b7w"/><ellipse class="g44-g4b7j"/></g><path class="kf-yc1b0m"/><path class="iyzlbd2fv"/><path class="pyvdlg5ra"/><path class="qf608obxe"/><radialGradient id="SVGQePX4dyT" cx="24.737" cy="84.466" r="16.886" gradientTransform="rotate(187.833 -2.453 80.219)scale(-1 1.4052)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="x21lzsbti"/><stop offset="1" class="fwx9zn6gv"/></radialGradient><path fill="url(#SVGQePX4dyT)" class="mmhpzqbdo"/><radialGradient id="SVGQcnOc17X" cx="117.204" cy="-1548.272" r="61.738" gradientTransform="matrix(.9182 0 0 -.7823 -57.667 -1176.21)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="vlzxxcccm"/><stop offset=".333" class="yyspbo0js"/><stop offset=".941" class="xn5dksb-u"/><stop offset="1" class="a72as_i6q"/></radialGradient><path fill="url(#SVGQcnOc17X)" class="qy_kx3b_g"/><radialGradient id="SVG5hw9ib5A" cx="140.254" cy="998.92" r="33.431" gradientTransform="matrix(0 .9331 1.4131 0 -1362.23 -123.91)" gradientUnits="userSpaceOnUse"><stop offset=".003" class="vlzxxcccm"/><stop offset=".333" class="yyspbo0js"/><stop offset=".941" class="xn5dksb-u"/><stop offset="1" class="a72as_i6q"/></radialGradient><path fill="url(#SVG5hw9ib5A)" class="ebmt93bdl"/><path class="wbj3i8f5f"/><path class="wvpw6p6sk"/><g class="z4n2hhy8u"><radialGradient id="SVG7mRSzb1n" cx="191.424" cy="-1029.154" r="41.908" gradientTransform="rotate(6.367 9004.37 -634.415)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="kvwb2tr-m"/><stop offset="1" class="rwhk7-m5g"/></radialGradient><path fill="url(#SVG7mRSzb1n)" class="g13f6nnoe"/></g><path class="hpzbe9b0v"/><radialGradient id="SVGStX5UcNt" cx="42.487" cy="-1219.828" r="48.964" gradientTransform="rotate(178.66 7.46 -593.067)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ohm06yblq"/><stop offset=".227" class="sgk-90bby"/><stop offset=".494" class="n3oe5lbqh"/><stop offset=".779" class="hj70ehb0j"/><stop offset="1" class="hunkxc7oa"/></radialGradient><path fill="url(#SVGStX5UcNt)" class="z3-bicb0r"/><radialGradient id="SVGqrLQBdRD" cx="93.198" cy="48.415" r="13.61" gradientTransform="matrix(1 0 0 -1 0 130)" gradientUnits="userSpaceOnUse"><stop offset="0" class="g8g9_37cy"/><stop offset=".04" class="ymxhfbcvi"/><stop offset=".517" class="wb84icb0c"/><stop offset="1" class="o_4j53rwc"/></radialGradient><path fill="url(#SVGqrLQBdRD)" class="llacf8y8l"/><path class="d5bjojbfp"/><radialGradient id="SVGmGV0qeJV" cx="-14.402" cy="165.915" r="21.685" gradientTransform="matrix(-.635 -.7725 -.8167 .6714 227.452 -7.606)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="jb0j4_2gw"/><stop offset="1" class="s6rm2gd3x"/></radialGradient><path fill="url(#SVGmGV0qeJV)" class="cvmn5ibdg"/><radialGradient id="SVGX4ZSKe2D" cx="75.215" cy="-22.348" r="15.889" gradientTransform="rotate(-58.04 162.26 20.047)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></radialGradient><path fill="url(#SVGX4ZSKe2D)" class="u10yjbbpw"/><radialGradient id="SVG9yWg9brx" cx="94.589" cy="-24.964" r="15.873" gradientTransform="matrix(.9078 -.4835 -.4667 -.8846 12.279 114.826)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></radialGradient><path fill="url(#SVG9yWg9brx)" class="s-b5fqa9x"/><radialGradient id="SVGHxhnJlgR" cx="89.402" cy="-31.464" r="18.06" gradientTransform="rotate(-41.201 188.36 19.083)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></radialGradient><path fill="url(#SVGHxhnJlgR)" class="udla4kykn"/><radialGradient id="SVGTys2FdSR" cx="97.041" cy="-34.279" r="17.259" gradientTransform="rotate(-33.051 210.696 22.44)scale(1 -1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></radialGradient><path fill="url(#SVGTys2FdSR)" class="m4ng1eb5v"/><radialGradient id="SVGanKnBbil" cx="80.973" cy="-26.303" r="17.265" gradientTransform="rotate(129.62 -8.76 81.028)scale(-1 1)" gradientUnits="userSpaceOnUse"><stop offset="0" class="s6rm2gd3x"/><stop offset="1" class="jb0j4_2gw"/></radialGradient><path fill="url(#SVGanKnBbil)" class="sbsu-9xql"/><path class="dptngybfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:detective-light-skin-tone" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.b-xyrbc2z {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M85.23 81.6c-1.25-2.27.34-4.58 3.06-7.44c4.31-4.54 9-15.07 4.64-25.76c.03-.06-.86-1.86-.83-1.92l-1.79-.09c-.57-.08-20.26-.12-39.97-.12s-39.4.04-39.97.12c0 0-2.65 1.95-2.63 2.01c-4.35 10.69.34 21.22 4.64 25.76c2.71 2.86 4.3 5.17 3.06 7.44c-1.21 2.21-4.81 2.53-4.81 2.53s.83 2.26 2.83 3.48c1.85 1.13 4.13 1.39 5.7 1.43c0 0 6.15 3.51 22.23 3.51h17.9c16.08 0 22.23-3.51 22.23-3.51c1.57-.04 3.85-.3 5.7-1.43c2-1.22 2.83-3.48 2.83-3.48s-3.61-.32-4.82-2.53");
}

.b9vy7ub3a {
  d: path("m46.6 123.9l-3.2-27.4c-.2-.8-.8-1.4-1.5-1.4c-.8.1-1.6.1-2.3.1c-7.8 0-14.8-3.2-18.3-5.2l11.4 33.9z");
}

.bcon_cs6f {
  d: path("M7.73 48.4c-4.24 10.35.23 21.01 4.41 25.5c.57.62 3.01 3.01 3.57 4.92c0 0 9.54-13.31 12.39-21.13c.58-1.58 1.1-3.2 1.17-4.88c.05-1.26-.14-2.76-.87-3.83c-.89-1.31-1.93-.96-3.44-.96c-2.88 0-15.49-.74-16.47-.74c.01.03-.76 1.12-.76 1.12");
}

.cvjflgbcp {
  stop-color: var(--svg-color--626262, #626262);
}

.cvmn5ibdg {
  d: path("M101.53 97.62c-.82.87-1.56 1.81-2.12 2.86c-.81 1.5-8.06 4.3-4.06 10.29c1.17 1.61 4.82 6.69 8.02 8.1c6.69 2.95 16.21-6.33 17.1-6.82c5.6-3.05-8.94-17.41-13.34-17.3c-.53.04-1.32.19-2.03.3c-1.37.24-2.71 1.67-3.57 2.57");
}

.d5bjojbfp {
  fill: var(--svg-color--ababab, #ababab);
  d: path("M96.6 80.4L90.8 85c-.7.5-1.6.4-2.1-.2l-.4-.6c-.5-.7-.4-1.6.2-2.1l5.8-4.7c.7-.5 1.6-.4 2.1.2l.4.6c.6.7.5 1.6-.2 2.2");
}

.d5o-7dbzj {
  stop-color: var(--svg-color--4b4b4b, #4b4b4b);
}

.dptngybfp {
  fill: var(--svg-color--edbd82, #edbd82);
  d: path("M118.86 101.51c-.6-.97-7.14 5.5-8.6 5.44c-1.67-.07-2.82-1.81-2.01-3.33c.92-1.71 7.58-7.21 7.28-7.59c-.56-.71-7.88 8.24-10.39 5.07c-1.56-1.96.55-3.56 1.77-4.9c.72-.79 4.2-3.9 4-4.16c-.2-.25-1.04.52-1.15.59c-.72.45-4.77 4.08-5.72 5.24c-1.57 1.92-1.21 3.35-.61 4.21c.7 1.01 1.43 2.5 1.83 3.66c.84 2.47-.16 6.13-.03 6.45c.14.34 1.12-1.69 1.31-3.51c.11-1.07 1.15-1.4 1.99-.72c.51.42.96.82 1.12 1.04c.34.46 2.36 3.15 2.91 4.18c.21.4.4.7.81 1.01c.3.23.64.4 1.01.5c1.64.45 3.17-.58 4.41-1.44c.74-.52 3.86-2.4 4.23-3.3c-1.61 1.2-7.11 5.64-8.55 3.28c-.78-1.34.6-1.85 1.48-2.41c1-.63 2.77-1.95 3.63-2.76c.24-.23 1.63-1.25 1.48-1.45c-.23-.29-3.13 1.87-3.46 2.11c-1.19.85-3.49 2.91-5.08 1.94c-.58-.36-.99-1.04-.99-1.73c0-1.66 7.64-6.92 7.33-7.42");
}

.ebmt93bdl {
  d: path("M64.6 4.44c-2.8-.73-7.4-.41-10.2 0c-7.1 1.25-6.1.52-12.8-.1c-2.7-.31-6.3-.52-8.9.31c-10 3.12-11.2 11.94-17.5 25.44c.1 12.36 70 12.25 69.9 0C79 17.21 75 7.24 64.6 4.44");
}

.edr3jwbtv {
  fill: var(--svg-color--312d2d, #312d2d);
}

.fbu7rg8-d {
  cx: 87.7px;
  cy: 105.3px;
  r: 0.6px;
}

.fk7-i2x1l {
  cx: 106.5px;
  cy: 114.4px;
  fill: var(--svg-color--404042, #404042);
  rx: 8.7px;
  ry: 8px;
}

.fos5e643c {
  stop-color: var(--svg-color--2b2b2b, #2b2b2b);
}

.fwx9zn6gv {
  stop-color: var(--svg-color--454140, #454140);
}

.g13f6nnoe {
  d: path("M90.3 43.4c7.3 9.2 5.8 22.7-3.3 30.1s-22.6 5.8-30-3.4s-5.8-22.7 3.4-30.1s22.5-5.8 29.9 3.4");
}

.g44-g4b7j {
  cx: 65.86px;
  cy: 60.13px;
  rx: 5.92px;
  ry: 6.13px;
}

.g8g9_37cy {
  stop-color: var(--svg-color--ffa726, #ffa726);
}

.g8wv28bsg {
  d: path("M19.26 84.91c4.28-6.5-5.21-8.93-5.21-8.93l-.01.01c1.65 2.05 2.4 3.84 1.43 5.61c-1.21 2.21-4.81 2.53-4.81 2.53s4.9 4.36 8.6.78");
}

.hj70ehb0j {
  stop-color: var(--svg-color--b5b5b5, #b5b5b5);
}

.hm99f6b5d {
  d: path("M81.43 84.91c-4.28-6.5 5.21-8.93 5.21-8.93l.01.01c-1.65 2.05-2.4 3.84-1.43 5.61c1.21 2.21 4.81 2.53 4.81 2.53s-4.91 4.36-8.6.78");
}

.ho7jlzxwz {
  cx: 10.4px;
  cy: 105.3px;
  r: 0.6px;
}

.hpzbe9b0v {
  fill: var(--svg-color--c7c7c7, #c7c7c7);
  d: path("m101.16 85.78l-5.68 4.52l-12.64-15.78L88.52 70z");
}

.hq1vc1g6j {
  cx: 12.2px;
  cy: 105.6px;
  r: 0.6px;
}

.hunkxc7oa {
  stop-color: var(--svg-color--9e9e9e, #9e9e9e);
}

.itte6eubh {
  fill: var(--svg-color--edc391, #edc391);
  d: path("M77.36 50.37H22.7c-5.89 0-10.71 5.14-10.71 11.41c0 6.28 4.82 11.41 10.71 11.41h54.65c5.89 0 10.71-5.14 10.71-11.41c.01-6.28-4.81-11.41-10.7-11.41");
}

.ixuczfbhb {
  stop-color: var(--svg-color--595959, #595959);
}

.iyzlbd2fv {
  fill: var(--svg-color--dba689, #dba689);
  d: path("M53.89 67.8c-.11-.04-.21-.07-.32-.08H46.5c-.11.01-.22.04-.32.08c-.64.26-.99.92-.69 1.63s1.71 2.69 4.55 2.69s4.25-1.99 4.55-2.69c.29-.7-.06-1.37-.7-1.63");
}

.jb0j4_2gw {
  stop-color: var(--svg-color--f9ddbd, #f9ddbd);
}

.jxlhhchve {
  fill: var(--svg-color--gray, gray);
  d: path("M92.67 103.86c-6.57-7.8-18.24-6.85-18.82-6.55l-.3.15l-4.99 10.12l2.25-.72c2.48-.8 7.15-.53 15.25 5.22c.32.27.68.38 1.05.38c1 0 2.07-.81 2.65-1.5l3.15-3.76c.72-1.02.63-2.3-.24-3.34");
}

.kf-yc1b0m {
  fill: var(--svg-color--454140, #454140);
  d: path("M41.89 50.83c-.93-1.23-3.07-3.01-7.23-3.01s-6.31 1.79-7.23 3.01c-.41.54-.31 1.17-.02 1.55c.26.35 1.04.68 1.9.39s2.54-1.16 5.35-1.18c2.81.02 4.49.89 5.35 1.18s1.64-.03 1.9-.39c.29-.38.39-1-.02-1.55m33.59-.24c-1.11-1.47-3.68-3.61-8.67-3.61s-7.56 2.14-8.67 3.61c-.49.65-.37 1.4-.03 1.86c.32.42 1.25.81 2.28.46s3.05-1.39 6.42-1.42c3.37.02 5.39 1.07 6.42 1.42s1.96-.04 2.28-.46c.33-.46.46-1.21-.03-1.86");
}

.kszhj0bry {
  fill: var(--svg-color--bdbdbd, #bdbdbd);
  d: path("M58.58 123.9L60.6 105H39.4l2.68 18.9z");
}

.kvwb2tr-m {
  stop-color: var(--svg-color--fafafa, #fafafa);
}

.llacf8y8l {
  d: path("m113.1 100.6l-.4-.5c-.4-3.4-2.4-7.9-5.8-12.2c-3-3.8-6.4-6.6-9.4-7.9c-.8-.4-1.5-1-2.1-1.7l-.8-1l-6.2 5l.8 1q.9 1.05 1.2 2.4C91 89 93 93 96 96.7c3.4 4.3 7.3 7.3 10.5 8.4l.4.5c.4.5 1 .8 1.7.8c.5 0 .9-.2 1.3-.5l.9-.7c.2-.1.4-.2.6-.4c.2-.1.3-.3.5-.5l.9-.7c.9-.7 1.1-2.1.3-3");
}

.m4ng1eb5v {
  d: path("m110.88 91.9l-6.19 6.28c-.93.92-1.03 2.33-.28 3.32c.8 1.09 2.4 1.23 3.54.38l7.06-5.32c1.31-1 1.57-2.87.53-4.07l-.53-.61c-1.08-1.21-2.97-1.21-4.13.02");
}

.mb-144bpe {
  d: path("M92.95 48.4c4.25 10.35-.22 21.01-4.41 25.51c-.57.62-3.01 3.01-3.57 4.92c0 0-9.54-13.31-12.39-21.13c-.57-1.58-1.1-3.2-1.17-4.88c-.05-1.26.14-2.76.87-3.83c.89-1.31 20.16-1.7 20.16-1.7c0 .02.51 1.11.51 1.11");
}

.mmhpzqbdo {
  d: path("M10.7 35.33c-2.37 2.1-5.56 6.79-3.21 12.61c1.77 4.39 8.09 6.29 8.09 6.29c0 .02 1.26.4 1.91.4l1.48-21.9c-3.03 0-5.94.91-7.82 2.22c.03.03-.46.35-.45.38");
}

.n3oe5lbqh {
  stop-color: var(--svg-color--cdcdcd, #cdcdcd);
}

.ndz8cojbi {
  cx: 11.3px;
  cy: 105.5px;
  r: 2.7px;
  fill: var(--svg-color--757575, #757575);
  stroke: var(--svg-color--9e9e9e, #9e9e9e);
  stroke-miterlimit: 10;
}

.o_4j53rwc {
  stop-color: var(--svg-color--fb8c00, #fb8c00);
}

.ohm06yblq {
  stop-color: var(--svg-color--e0e0e0, #e0e0e0);
}

.p6dl0tbxz {
  fill: var(--svg-color--f9ddbd, #f9ddbd);
  d: path("M50.03 11c-17.4 0-33.52 18.61-33.52 45.39c0 26.64 16.61 39.81 33.52 39.81s33.52-13.17 33.52-39.81C83.55 29.61 67.43 11 50.03 11");
}

.pl8-kjvjg {
  d: path("M50.1 95.4H50c-18.1 0-36.8 3.7-46 12.2v16.3h98v-3.4c0-16.8-26.3-25.1-51.9-25.1");
}

.pyvdlg5ra {
  fill: var(--svg-color--444, #444);
  d: path("M58.56 75.89c-3.19 1.89-13.63 1.89-16.81 0c-1.83-1.09-3.7.58-2.94 2.24c.75 1.63 6.45 5.42 11.37 5.42s10.55-3.79 11.3-5.42c.75-1.67-1.09-3.33-2.92-2.24");
}

.qf608obxe {
  fill: var(--svg-color--312d2d, #312d2d);
  d: path("M66.86 7.62c-13.23-4.19-21.84.51-26.47 3.03c-.96.52-30.16 22.51-29.46 24.48c-2.52 2.14-5.69 6.69-3.52 12.6c1.64 4.45 8.17 6.5 8.17 6.5c-.46 8.01 1.03 12.94 1.82 14.93c.14.35.63.32.72-.04c.99-3.96 4.36-17.8 4.03-20.21c0 0 11.34-2.25 22.17-10.22c2.2-1.62 4.59-3 7.13-4.01c13.6-5.41 16.45 3.82 16.45 3.82s9.42-1.81 12.26 11.27c1.07 4.9 1.79 12.75 2.4 18.24c.04.39.57.47.72.11c.95-2.18 2.85-6.5 3.3-10.91c.16-1.55 3.81-5.62 5.6-12.27c2.41-8.88-20.43-35.76-25.32-37.32");
}

.qy_kx3b_g {
  d: path("M83.5 26.76c-4.5-1.14-10.9-2.08-17-2.7c-5.1-.52-10.7.52-16.5.52s-11.4-1.04-16.5-.52c-6.1.52-13.7 2.7-18.2 3.84C7.5 29.88 4 31.95 4 34.86s4.1 4.26 12 6.23c4.5 1.14 8 3.74 15.9 4.67c5.1.62 13.6-1.25 19.3-1.25c5.8 0 13.4 1.87 18.5 1.35c6.1-.52 9.7-3.01 14.2-4.15c7.9-1.97 12-4.05 12-6.96s-4.5-6.02-12.4-7.99");
}

.rwhk7-m5g {
  stop-color: var(--svg-color--eee, #eee);
}

.s-b5fqa9x {
  d: path("M98.35 114.61s1.74-.08 4.02-.72c6.9-1.96 2.59-8.93 1.94-10.03c-3.31-5.64 2.14-7.99 5.8-11.2c.76-.67 3.18-3.19 2.54-5.57c-1.53-3.61-4.58-1.2-11.4 3.39c-1.86 1.25-3.6 2.63-5.17 4.23c-7.5 7.59-.97 16.25 2.27 19.9");
}

.s6rm2gd3x {
  stop-color: var(--svg-color--ffd29c, #ffd29c);
}

.sbsu-9xql {
  d: path("m117.65 102.04l-6.13 5.25c-.93.76-1.13 2.04-.52 3c.64 1.06 2.08 1.32 3.19.63l6.85-4.31c1.28-.81 1.67-2.49.81-3.67l-.43-.6c-.89-1.17-2.61-1.32-3.77-.3");
}

.sgk-90bby {
  stop-color: var(--svg-color--dbdbdb, #dbdbdb);
}

.sozvcjboj {
  stop-color: var(--svg-color--262626, #262626);
}

.u_6s-xoka {
  stop-color: var(--svg-color--707070, #707070);
}

.u10yjbbpw {
  d: path("m119.9 107.09l-5.74 4.2c-.75.52-.98 1.47-.58 2.23c.42.84 1.49 1.12 2.37.68l6.22-3.44c1.01-.53 1.41-1.77.84-2.71l-.29-.48c-.6-.96-1.89-1.18-2.82-.48");
}

.udla4kykn {
  d: path("m114.64 96.58l-7.56 6.87c-1.02.91-.41 1.75.32 2.82c.78 1.18 1.64 2.04 2.88 1.21l8.41-5.83c1.42-.98 1.79-2.91.77-4.21l-.52-.66c-1.06-1.32-3.02-1.42-4.3-.2");
}

.ugadeyb1e {
  d: path("M67.4 123.9L78.8 90c-3.5 2-10.6 5.2-18 5.2c-.9 0-1.8 0-2.6-.2h-.1c-.6 0-1.2.6-1.4 1.4l-3.4 27.5z");
}

.v--k8egri {
  fill: var(--svg-color--edc391, #edc391);
  d: path("M59.4 93.42H41.24v9.98c0 4.51 3.7 8.17 8.26 8.17h1.65c4.56 0 8.26-3.66 8.26-8.17v-9.98z");
}

.v17w-n78o {
  fill: var(--svg-color--gray, gray);
  d: path("m24.55 97.46l-.3-.15c-.59-.29-12.34-1.25-18.81 6.56c-.87 1.04-.96 2.32-.2 3.38l3.1 3.7c.71.85 1.69 1.51 2.61 1.51c.36 0 .72-.1 1.04-.33c8.17-5.79 12.84-6.06 15.32-5.26l2.25.72z");
}

.ves7lbs2g {
  fill: var(--svg-color--616161, #616161);
  d: path("m116.99 123.9l-2.19-11.5l-9.9-2.5c-3.3-.8-6.5 1.3-7 4.7c0 0-.71 2.8-2.21 9.3z");
}

.vlzxxcccm {
  stop-color: var(--svg-color--757575, #757575);
}

.vnlt8_bly {
  stop-color: var(--svg-color--606060, #606060);
}

.vtk1xpb3x {
  cx: 85.8px;
  cy: 105.6px;
  r: 0.6px;
}

.wb84icb0c {
  stop-color: var(--svg-color--ff9800, #ff9800);
}

.wbj3i8f5f {
  fill: var(--svg-color--eee, #eee);
  d: path("M38.8 10.35c3.2 2.28 7.1 3.43 11 2.91c3.5-.41 6.9-1.77 10.1-3.32c.5-.31 1.1.31.9.94c-.5 1.35-5.5 6.44-11.4 6.44c-5.5 0-9.2-2.39-11.1-5.82c-.4-.52-.2-1.66.5-1.15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.wp5yo6b7w {
  cx: 34.46px;
  cy: 58.75px;
  rx: 4.93px;
  ry: 5.1px;
}

.wvpw6p6sk {
  fill: var(--svg-color--404042, #404042);
  d: path("M82.1 23.44c-11.6 6.85-52.3 6.85-63.8-.1c-1 2.18-2 4.47-3 6.75c.1 12.36 70 12.25 69.9 0c-1.1-2.19-2.1-4.47-3.1-6.65");
}

.x21lzsbti {
  stop-color: var(--svg-color--454140, #454140);
  stop-opacity: 0;
}

.xn5dksb-u {
  stop-color: var(--svg-color--464646, #464646);
}

.xv67-cbxy {
  fill: var(--svg-color--424242, #424242);
}

.yfzjuybrm {
  fill: var(--svg-color--404042, #404042);
  d: path("M50.1 79.99c-15.96 0-28.99 4.06-28.99 8.97c0 3.12 4.91 5.76 12.37 7.37c4.06.85 7.46 22.1 12.28 27.57h5.95c8.4-5.57 16.9-27.57 21.53-29.56c3.59-1.51 5.76-3.4 5.76-5.38c-.01-5-12.94-8.97-28.9-8.97");
}

.yizguit1x {
  cx: 86.7px;
  cy: 105.5px;
  r: 2.7px;
  fill: var(--svg-color--757575, #757575);
  stroke: var(--svg-color--9e9e9e, #9e9e9e);
  stroke-miterlimit: 10;
}

.ymxhfbcvi {
  stop-color: var(--svg-color--ffa623, #ffa623);
}

.yyspbo0js {
  stop-color: var(--svg-color--686868, #686868);
}

.z3-bicb0r {
  d: path("M92.5 41.3C84.1 30.7 68.8 29 58.3 37.5s-12.2 23.9-3.8 34.4s23.7 12.3 34.2 3.8s12.2-23.9 3.8-34.4m-7.36 29.87c-8.04 6.43-19.78 5.2-26.21-2.93s-5.11-19.87 2.93-26.4s19.78-5.2 26.21 2.93c6.44 8.13 5.11 19.96-2.93 26.4");
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

</style>
