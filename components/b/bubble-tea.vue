<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="c00felxqd"/><linearGradient id="SVG96SM2bSn" x1="63.85" x2="63.85" y1="71.279" y2="93.528" gradientUnits="userSpaceOnUse"><stop offset="0" class="zs_40wirf"/><stop offset="1" class="tsknpvc8g"/></linearGradient><path fill="url(#SVG96SM2bSn)" class="yr76v8ifd"/><radialGradient id="SVGBhyofeud" cx="50.2" cy="68.106" r="67.101" gradientTransform="matrix(.9469 .3217 -.2221 .6538 17.794 7.434)" gradientUnits="userSpaceOnUse"><stop offset="0" class="wei60eblx"/><stop offset="1" class="zs_40wirf"/></radialGradient><path fill="url(#SVGBhyofeud)" class="keo3tvb6k"/><path class="a72ze6b7d"/><radialGradient id="SVGHjQrzbgD" cx="86.055" cy="82.907" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGHjQrzbgD)" class="m6rbb4bkc"/><radialGradient id="SVGHtrxcdEX" cx="70.289" cy="81.575" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGHtrxcdEX)" class="ru4ypyhqm"/><radialGradient id="SVGZKCFCcUH" cx="60.776" cy="102.577" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGZKCFCcUH)" class="uhli10b2r"/><radialGradient id="SVGQ3whCpoE" cx="74.424" cy="101.896" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGQ3whCpoE)" class="ui1x8bb2q"/><radialGradient id="SVGyByOhcGc" cx="73.936" cy="104.452" r="5.638" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset=".528" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><ellipse fill="url(#SVGyByOhcGc)" class="ui1x8bb2q"/><radialGradient id="SVG4Bf5zR8v" cx="69.424" cy="84.239" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><ellipse fill="url(#SVG4Bf5zR8v)" class="ru4ypyhqm"/><radialGradient id="SVG1UIMt3ST" cx="85.189" cy="85.571" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><ellipse fill="url(#SVG1UIMt3ST)" class="m6rbb4bkc"/><radialGradient id="SVGEF33hrAP" cx="44.286" cy="102.117" r="5.22" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGEF33hrAP)" class="iqj86obko"/><radialGradient id="SVGMDrJ9CJC" cx="43.366" cy="104.22" r="5.522" gradientTransform="matrix(1 0 0 .9179 0 9.179)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><ellipse fill="url(#SVGMDrJ9CJC)" class="iqj86obko"/><radialGradient id="SVGDzt3hbdm" cx="83.471" cy="108.501" r="5.22" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGDzt3hbdm)" class="nv344kbli"/><radialGradient id="SVG70Fcsboy" cx="82.551" cy="110.603" r="5.522" gradientTransform="matrix(1 0 0 .9179 0 9.511)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><ellipse fill="url(#SVG70Fcsboy)" class="nv344kbli"/><radialGradient id="SVGh5remeqf" cx="59.568" cy="105.661" r="6.038" gradientTransform="matrix(1 0 0 .9179 0 9.254)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVGh5remeqf)" class="i77odkben"/><radialGradient id="SVGuCvaAdXX" cx="66.854" cy="114.097" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGuCvaAdXX)" class="a2s-j3boc"/><radialGradient id="SVG7c6xNcNo" cx="65.645" cy="117.181" r="5.785" gradientTransform="matrix(1 0 0 .9284 0 8.616)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVG7c6xNcNo)" class="dgjbt72cu"/><radialGradient id="SVG2HlnRcEQ" cx="53.402" cy="93.717" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVG2HlnRcEQ)" class="ce4wdbcpv"/><radialGradient id="SVGmFsmMb0Q" cx="52.194" cy="96.801" r="6.038" gradientTransform="matrix(1 0 0 .9179 0 8.793)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVGmFsmMb0Q)" class="dh35brbfz"/><radialGradient id="SVGcUM2mbvR" cx="65.533" cy="91.96" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGcUM2mbvR)" class="qyf3uv8wo"/><radialGradient id="SVGu6MuLbNp" cx="64.325" cy="95.044" r="5.725" gradientTransform="matrix(1 0 0 .9565 0 5.032)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVGu6MuLbNp)" class="heykc6osl"/><radialGradient id="SVGkhiEXdFj" cx="80.097" cy="95.907" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGkhiEXdFj)" class="d779n7jli"/><radialGradient id="SVGEJEL1bsd" cx="78.7" cy="98.342" r="5.928" gradientTransform="matrix(1 0 0 .9179 0 8.873)" gradientUnits="userSpaceOnUse"><stop offset=".507" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVGEJEL1bsd)" class="pw8ixmbxm"/><radialGradient id="SVGpvYoqdJI" cx="43.954" cy="85.416" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGpvYoqdJI)" class="nf6ce2bbi"/><radialGradient id="SVG2neRwPCA" cx="42.746" cy="88.501" r="6.038" gradientTransform="matrix(1 0 0 .9681 0 3.916)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVG2neRwPCA)" class="lwxiguy5e"/><radialGradient id="SVGHxEtSYvX" cx="52.757" cy="111.04" r="5.668" gradientTransform="matrix(1 0 0 .9699 0 3.75)" gradientUnits="userSpaceOnUse"><stop offset="0" class="no9o3hbeo"/><stop offset=".999" class="cj1wkwbdw"/></radialGradient><ellipse fill="url(#SVGHxEtSYvX)" class="tqfi275jf"/><radialGradient id="SVGNoWyWb5j" cx="51.549" cy="114.448" r="5.985" gradientTransform="matrix(1 0 0 .9702 0 3.724)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="jkoiuq_tf"/><stop offset="1" class="tsknpvc8g"/></radialGradient><path fill="url(#SVGNoWyWb5j)" class="capwxhq0w"/><path class="zfi9x6b0l"/><path class="ad7uloe5c"/><path class="ahwrcybts"/><path class="bl8-r1ytt"/><ellipse transform="rotate(-74.585 86.264 9.084)" class="svozyobap"/><path class="fcb92ryyw"/><path class="zu32urbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:bubble-tea" /></template>
<style>
.a2s-j3boc {
  cx: 65.72px;
  cy: 117.13px;
  rx: 4.76px;
  ry: 4.61px;
}

.a72ze6b7d {
  fill: var(--svg-color--9575cd, #9575cd);
  d: path("M70.5 38.41c-2.3 8.03-8.97 29.65-8.97 29.65s2.94 2.3 7.83 2.31c5.33 0 6.17-2.09 6.17-2.09s6.55-21.27 8.78-29.18c0 0-2.12.37-7.41.33c-5.31-.03-6.4-1.02-6.4-1.02");
}

.ad7uloe5c {
  fill: var(--svg-color--72e6ac, #72e6ac);
  d: path("M63.92 23.35c-21.49 0-37.91 5.15-37.91 11.5s16.41 11.5 37.91 11.5s37.91-5.15 37.91-11.5s-16.42-11.5-37.91-11.5m12.84 15.29c-4.76 0-8.61-1.38-8.61-3.07c0-1.7 3.86-3.07 8.61-3.07s8.61 1.38 8.61 3.07c0 1.7-3.86 3.07-8.61 3.07");
}

.ahwrcybts {
  fill: var(--svg-color--b39ddb, #b39ddb);
  d: path("M87.81 4.7c-3.95-1.06-7.16.05-8.06 2.61l-9.07 30.52s1.85.96 7.42.96c4.55 0 7.03-2.25 7.03-2.25s7.07-25 7.36-25.98c.68-2.24-1.23-4.93-4.68-5.86");
}

.bl8-r1ytt {
  fill: var(--svg-color--9575cd, #9575cd);
  d: path("M78.1 38.79c4.55 0 7.03-2.25 7.03-2.25l1.1-3.89s-3.83 2.92-7.91 3.87c-4.38 1.02-7.64 1.31-7.64 1.31s1.85.96 7.42.96");
}

.c00felxqd {
  fill: var(--svg-color--bae2fd, #bae2fd);
  d: path("M63.93 25.32c-34.12.31-37.92 9.54-37.92 9.54s9.7 68.61 10.71 75.34s12.54 13.51 27.21 13.51s26.2-6.79 27.21-13.51c1.01-6.73 10.83-74.88 10.83-74.88s-3.92-9.69-38.04-10");
  opacity: var(--svg-opacity--0-85, 0.85);
}

.capwxhq0w {
  d: path("M46.82 114.17c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.12-4.75-2.08-4.75-4.62");
}

.ce4wdbcpv {
  cx: 52.27px;
  cy: 97.36px;
  rx: 4.76px;
  ry: 4.61px;
}

.cj1wkwbdw {
  stop-color: var(--svg-color--3d3832, #3d3832);
}

.d779n7jli {
  cx: 78.96px;
  cy: 99.49px;
  rx: 4.76px;
  ry: 4.61px;
}

.dgjbt72cu {
  d: path("M60.92 117.13c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.11-4.75-2.07-4.75-4.62");
}

.dh35brbfz {
  d: path("M47.47 97.36c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.11-4.75-2.07-4.75-4.62");
}

.fcb92ryyw {
  fill: var(--svg-color--33ac71, #33ac71);
  d: path("m71.73 34.3l.45-1.51c-.59.16-1.22.36-1.83.62c-1.32.55-2.03 1.02-2.21 1.97c-.15.8.63 1.4.63 1.4s-.04-.67.33-1.05c.76-.79 1.2-.96 2.63-1.43");
}

.heykc6osl {
  d: path("M59.6 95.66c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.12-4.75-2.07-4.75-4.62");
}

.i77odkben {
  d: path("M54.84 105.96c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.12-4.75-2.08-4.75-4.62");
}

.iqj86obko {
  cx: 43.24px;
  cy: 105.3px;
  rx: 4.38px;
  ry: 4.25px;
}

.jkoiuq_tf {
  stop-color: var(--svg-color--f5cea7, #f5cea7);
  stop-opacity: 0;
}

.keo3tvb6k {
  d: path("M97.22 64.04c1.81 4.57-7.43 19.27-33.89 8.04C38.24 61.42 30.3 64.3 30.3 64.3c3.68-3.67 11.07-8.7 29.26-8.7c20.63 0 35.48 2.92 37.66 8.44");
}

.lwxiguy5e {
  d: path("M38.02 89.31c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.11-4.75-2.07-4.75-4.62");
}

.m6rbb4bkc {
  cx: 84.92px;
  cy: 86.88px;
  rx: 4.76px;
  ry: 4.61px;
}

.nf6ce2bbi {
  cx: 42.82px;
  cy: 89.31px;
  rx: 4.76px;
  ry: 4.61px;
}

.no9o3hbeo {
  stop-color: var(--svg-color--6d4c41, #6d4c41);
}

.nv344kbli {
  cx: 82.43px;
  cy: 111.49px;
  rx: 4.38px;
  ry: 4.25px;
}

.pw8ixmbxm {
  d: path("M74.16 99.49c0-2.55 1.94-4.46 4.56-4.61c2.61-.15 5.04 1.81 5.04 4.36s-1.64 5-4.85 4.87c-2.62-.12-4.75-2.07-4.75-4.62");
}

.qyf3uv8wo {
  cx: 64.4px;
  cy: 95.66px;
  rx: 4.76px;
  ry: 4.61px;
}

.ru4ypyhqm {
  cx: 69.16px;
  cy: 85.58px;
  rx: 4.76px;
  ry: 4.61px;
}

.svozyobap {
  cx: 86.26px;
  cy: 9.08px;
  fill: var(--svg-color--7e57c2, #7e57c2);
  rx: 3.5px;
  ry: 5.16px;
}

.tqfi275jf {
  cx: 51.62px;
  cy: 114.16px;
  rx: 4.76px;
  ry: 4.61px;
}

.tsknpvc8g {
  stop-color: var(--svg-color--f5cea7, #f5cea7);
}

.uhli10b2r {
  cx: 59.64px;
  cy: 105.96px;
  rx: 4.76px;
  ry: 4.61px;
}

.ui1x8bb2q {
  cx: 73.29px;
  cy: 105.3px;
  rx: 4.76px;
  ry: 4.61px;
}

.wei60eblx {
  stop-color: var(--svg-color--c48c63, #c48c63);
}

.yr76v8ifd {
  d: path("M30.3 64.3c2.61 18.75 5.83 41.86 6.43 45.89c1.01 6.73 12.54 13.51 27.21 13.51s26.2-6.79 27.21-13.51c.59-3.95 3.68-26.07 6.26-44.66c0 0-24.45-9.08-39.2-7.27c-14.75 1.8-27.91 6.04-27.91 6.04");
}

.zfi9x6b0l {
  fill: var(--svg-color--33ac71, #33ac71);
  d: path("M101.31 40.11c.16-.93 1.09-3.65.52-5.62c0 0-2.08 9.1-37.83 9.1s-38.01-9-38.01-9c-.21 1.81.55 4.58.7 5.52c.51 3.05-1.66 3.01-1.66 3.01s.35 3.34 6.35 2.73c1.1-.11 3.97-.76 5.52 1c1.48 1.68 2.77 3.23 5.32 4.01c3.64 1.1 6.46-1.71 10.94-.75c2.76.59 4.52 2.3 9.23 2.8c5.21.56 7-2.19 9.8-2.6c5.06-.74 6.76 1.14 10.94 1.02c4.82-.13 6.4-2.45 8.24-3.71c2.72-1.86 4.97-.71 6.08-.6c6 .62 5.53-3.88 5.53-3.88s-2.18.01-1.67-3.03");
}

.zs_40wirf {
  stop-color: var(--svg-color--eeb68e, #eeb68e);
}

.zu32urbct {
  fill: var(--svg-color--fff, #fff);
  d: path("M33.33 57.21c-.86-6.66 5.83-7.34 6.93 5.14l.4 13.92s.52 3.99-1.44 4.42c-2.93.64-3.26-3.68-3.26-3.68S34 62.34 33.33 57.21");
  opacity: var(--svg-opacity--0-79, 0.79);
}

</style>
