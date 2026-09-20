<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGW5xGpddv)" class="g0hv7h42u"/><path fill="url(#SVGjjcQ5MGN)" class="phuspdbnj"/><path fill="url(#SVG5X5qKdxX)" class="ixhfpnbnk"/><path fill="url(#SVGZain3d1j)" class="p4-nmbcvt"/><path fill="url(#SVGR4X16jkh)" class="r5nd0jokb"/><path fill="url(#SVG32KgceAB)" class="fsf_-254e"/><path fill="url(#SVGUgZsAd5t)" class="yxe7vqbgs"/><path fill="url(#SVG5zXCObIb)" class="ymyprzg5j"/><path fill="url(#SVGxuUIvekm)" class="htj_d2b6q"/><path fill="url(#SVGhq7dYchR)" class="kisqh2b5x"/><path fill="url(#SVGgjha5k5Q)" clip-rule="evenodd" class="edfzmfvbk"/><path class="yr2tuwarl"/><path fill="url(#SVGLRI2bbjq)" class="gkphcdcxj"/><path fill="url(#SVGoZDaTpnV)" class="quqi49b8b"/><path fill="url(#SVGqxFbtdoF)" class="bjq2urfqt"/><path fill="url(#SVGcel1DAKU)" class="q920b_bde"/><path fill="url(#SVG5GaE8bQp)" class="jxu8kdb0h"/><path fill="url(#SVGvRiqQbkT)" class="bmxavx4yg"/><path fill="url(#SVGAqP7Sbwg)" clip-rule="evenodd" class="w65tc8z-r"/><path fill="url(#SVGpx1Dcc9o)" class="nb2-p543p"/><path fill="url(#SVG9JnS0dbA)" class="o4rgs-nvh"/><path class="ssx3e5b6i"/><path class="rezxhqr5u"/></g><defs><linearGradient id="SVGW5xGpddv" x1="13.31" x2="12.736" y1="4.715" y2="20.03" gradientUnits="userSpaceOnUse"><stop class="bd72xxbkx"/><stop offset=".18" class="ub-6xfjiy"/><stop offset=".39" class="ifuze0i5a"/><stop offset=".52" class="dhr4twb3r"/><stop offset=".77" class="tb_q_pbom"/><stop offset="1" class="e2g0nlbrt"/></linearGradient><linearGradient id="SVGjjcQ5MGN" x1="5.587" x2="11.634" y1="9.158" y2="18.166" gradientUnits="userSpaceOnUse"><stop class="xhz0a0yat"/><stop offset=".61" class="w90bhlbxp"/><stop offset="1" class="b9pdaabsh"/></linearGradient><linearGradient id="SVG5X5qKdxX" x1="5.026" x2="19.524" y1="4.03" y2="18.909" gradientUnits="userSpaceOnUse"><stop class="ogmq57gyo"/><stop offset="1" class="jmrlviers"/></linearGradient><linearGradient id="SVGZain3d1j" x1="5.001" x2="18.728" y1="4.043" y2="18.422" gradientUnits="userSpaceOnUse"><stop class="u4afi8bui"/><stop offset="1" class="nj75-ibfm"/></linearGradient><linearGradient id="SVGR4X16jkh" x1="5" x2="9.214" y1="4.001" y2="21.423" gradientUnits="userSpaceOnUse"><stop offset=".47" class="anzkasxyn"/><stop offset="1" class="asv2k-b4i"/></linearGradient><linearGradient id="SVG32KgceAB" x1="6.713" x2="12.454" y1="4.973" y2="21.948" gradientUnits="userSpaceOnUse"><stop class="nz7ytzbbn"/><stop offset=".49" class="fu1z21blc"/><stop offset=".76" class="vp11k1byg"/><stop offset="1" class="ab16m00kq"/></linearGradient><linearGradient id="SVGUgZsAd5t" x1="7.663" x2="11.611" y1="4.014" y2="20.683" gradientUnits="userSpaceOnUse"><stop class="ap0--cbue"/><stop offset=".41" class="mjcl0fb5o"/><stop offset=".56" class="su4r9jbcc"/><stop offset="1" class="apf9xrb8k"/></linearGradient><linearGradient id="SVG5zXCObIb" x1="6.346" x2="9.435" y1="3.593" y2="20.602" gradientUnits="userSpaceOnUse"><stop class="znk-7xb2j"/><stop offset=".35" class="r3alx330p"/><stop offset=".65" class="fy3x7tbar"/><stop offset="1" class="cl6ex92nj"/></linearGradient><linearGradient id="SVGxuUIvekm" x1="12.018" x2="12.018" y1="4" y2="19.999" gradientUnits="userSpaceOnUse"><stop class="cmkju7bum"/><stop offset="1" class="v6pb5cb6p"/></linearGradient><linearGradient id="SVGhq7dYchR" x1="11.999" x2="11.999" y1="4.001" y2="19.965" gradientUnits="userSpaceOnUse"><stop class="m7zpx_zla"/><stop offset="1" class="jm6wz4bih"/></linearGradient><linearGradient id="SVGgjha5k5Q" x1="11.999" x2="11.999" y1="4.005" y2="20" gradientUnits="userSpaceOnUse"><stop class="dzt0l2c3w"/><stop offset=".54" class="eg5f20k3o"/><stop offset="1" class="a6zmztb9a"/></linearGradient><linearGradient id="SVGLRI2bbjq" x1="19.649" x2="2.431" y1="4.058" y2="18.68" gradientUnits="userSpaceOnUse"><stop offset=".25" class="adf0nu6hs"/><stop offset=".38" class="csou9tqec"/><stop offset=".51" class="h10di2y6j"/><stop offset="1" class="f5y_yf0ix"/></linearGradient><linearGradient id="SVGoZDaTpnV" x1="18.264" x2="2.381" y1="4.059" y2="18.445" gradientUnits="userSpaceOnUse"><stop class="l52dqccet"/><stop offset=".36" class="xm9oltbko"/><stop offset="1" class="hrnp1g9bf"/></linearGradient><linearGradient id="SVGqxFbtdoF" x1="18.81" x2="9.113" y1="2.814" y2="22.101" gradientUnits="userSpaceOnUse"><stop class="g-5z62bsv"/><stop offset="1" class="js94kkmqa"/></linearGradient><linearGradient id="SVGcel1DAKU" x1="18.703" x2=".506" y1="1.198" y2="33.502" gradientUnits="userSpaceOnUse"><stop class="u01m3lmub"/><stop offset="1" class="m5_20ybwm"/></linearGradient><linearGradient id="SVG5GaE8bQp" x1="11.882" x2="11.882" y1="4" y2="20.025" gradientUnits="userSpaceOnUse"><stop class="lsctsibdo"/><stop offset=".54" class="jn24rbbbu"/><stop offset="1" class="j2ooxcbrl"/></linearGradient><linearGradient id="SVGvRiqQbkT" x1="16.946" x2="15.265" y1="5.122" y2="20.376" gradientUnits="userSpaceOnUse"><stop class="j1ae9bchu"/><stop offset=".44" class="uabxjjb7w"/></linearGradient><linearGradient id="SVGAqP7Sbwg" x1="11.998" x2="11.998" y1="3.996" y2="19.999" gradientUnits="userSpaceOnUse"><stop class="s3x0-rb2d"/><stop offset=".3" class="f_1wm2bfr"/><stop offset=".65" class="yyhdiub6i"/><stop offset="1" class="o8b3n_mlc"/></linearGradient><linearGradient id="SVGpx1Dcc9o" x1="17.76" x2="12.745" y1="4" y2="21.096" gradientUnits="userSpaceOnUse"><stop class="trzkvt_lc"/><stop offset=".34" class="c3sygxl8w"/><stop offset=".46" class="nxhea2bra"/><stop offset="1" class="b0q8ftb0o"/></linearGradient><linearGradient id="SVG9JnS0dbA" x1="17.76" x2="12.745" y1="4" y2="21.096" gradientUnits="userSpaceOnUse"><stop class="bz2v5bcyk"/><stop offset=".46" class="gz1v3ccid"/><stop offset="1" class="x1h0_9f7j"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cwar-background" /></template>
<style>
.a6zmztb9a {
  stop-color: var(--svg-color--f8c5c4, #f8c5c4);
}

.ab16m00kq {
  stop-color: var(--svg-color--5a3a3d, #5a3a3d);
}

.adf0nu6hs {
  stop-color: var(--svg-color--4a6266, #4a6266);
}

.anzkasxyn {
  stop-color: var(--svg-color--fffdfa, #fffdfa);
}

.ap0--cbue {
  stop-color: var(--svg-color--5a4f4e, #5a4f4e);
}

.apf9xrb8k {
  stop-color: var(--svg-color--5c4347, #5c4347);
}

.asv2k-b4i {
  stop-color: var(--svg-color--e1d6d8, #e1d6d8);
}

.b0q8ftb0o {
  stop-color: var(--svg-color--000600, #000600);
}

.b9pdaabsh {
  stop-color: var(--svg-color--9e3543, #9e3543);
  stop-opacity: 0.41;
}

.bd72xxbkx {
  stop-color: var(--svg-color--11638b, #11638b);
  stop-opacity: 0.2;
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bjq2urfqt {
  d: path("m18.494 17.65l-1.35 2.25l1.11-2.485l.745-.28v.28z");
}

.bmxavx4yg {
  d: path("M19 11.034c-.5.07-.92.49-.92 1c0 .415.25.765.605.925a1 1 0 0 1-.405-.83c0-.48.325-.88.72-.955z");
}

.bz2v5bcyk {
  stop-color: var(--svg-color--989fa0, #989fa0);
}

.c3sygxl8w {
  stop-color: var(--svg-color--8bc9d3, #8bc9d3);
}

.cl6ex92nj {
  stop-color: var(--svg-color--f9edf1, #f9edf1);
}

.cmkju7bum {
  stop-color: var(--svg-color--bfb1b1, #bfb1b1);
}

.csou9tqec {
  stop-color: var(--svg-color--939d9f, #939d9f);
}

.dhr4twb3r {
  stop-color: var(--svg-color--0b9bb4, #0b9bb4);
}

.dzt0l2c3w {
  stop-color: var(--svg-color--ffabb8, #ffabb8);
}

.e2g0nlbrt {
  stop-color: var(--svg-color--0e3650, #0e3650);
  stop-opacity: 0.45;
}

.edfzmfvbk {
  fill-rule: evenodd;
  d: path("M9.1 5.73c.05.1.13.34 0 .485c-.166.18.27.4.28.2V6.27c0-.235 0-.57.2-.45c.2.03.284.065.334.085c.025.01.04.02.06.02c.03 0 .065-.02.165-.075l.05-.03l.085-.05c.37-.23 1.11-.68 1.76-.14c.06.075.155.26.09.37c-.09.135-.175.35-.09.495c.09.145.01.37-.545.435c-.3.04-.515.2-.685.335c-.15.11-.27.2-.38.16l-.135-.05c-.14-.055-.215-.09-.375.05c-.1.09-.245.005-.41-.09c-.17-.1-.37-.22-.57-.165c-.3.075-.305.41-.305.63c0 .065 0 .12-.01.155c-.015.08-.1.115-.17.135c-.075.03-.13.05-.025.115l.12.065c.11.05.13.065-.045.19c-.225.17-.455.465-.185.755c0 .055-.05.085-.11.115c-.1.05-.21.1-.14.3c0 .05-.01.09-.015.13c-.025.105-.04.185.115.185c.06.02.2.085.26.19c.035.065 0 .09-.035.115c-.04.025-.07.05.035.11c.085.055.19.035.29.01c.13-.025.25-.05.31.095c.1.255.13.7 0 .775c-.105.06.105.235.225.315a.35.35 0 0 1 .09-.315c.06-.06.1-.06.15-.06s.125.005.25-.065c.125-.065.145-.125.15-.165c.015-.045.02-.065.126-.06c.2.01.074-.425-.12-.425c-.126 0-.126-.01-.15-.06c-.02-.035-.05-.08-.11-.155c-.176-.19-.3-.18-.416-.09c-.26.2-.535.17-.6.09a1 1 0 0 1-.08-.11a.6.6 0 0 0-.18-.195c-.065-.07-.065-.125-.06-.17c0-.03 0-.055-.015-.075c-.055-.07.005-.17.335-.135c.075.035.21.06.165-.1c-.055-.205.25-.1.27 0c.025.1.165.335.25.165a.26.26 0 0 0 .015-.225a.3.3 0 0 1-.015-.145a.4.4 0 0 0 0-.145a.4.4 0 0 1 .035-.26c.085-.2.075-.215-.075-.25c-.15-.03-.385-.11-.275-.29c.065-.105.1-.12.125-.125c.015-.005.025-.01.04-.045c.01-.03-.005-.125-.025-.24c-.03-.17-.07-.37-.01-.41c.1-.07.22-.045.46.09c.165.095.27.055.365.025a.4.4 0 0 1 .125-.025a.2.2 0 0 0 .11-.035c.05-.025.105-.055.25-.02c.15.035.19.005.25-.035a.5.5 0 0 1 .105-.07c.05-.02.085-.05.115-.08c.065-.05.12-.105.31-.1c.15.01.2-.06.245-.125c.04-.06.075-.115.18-.11h.005c.22.015.57.03.65-.325c.045-.23.08-.295.12-.37l.085-.18c.085-.235.2-1.025 0-1.1c-.06-.025-.105-.06-.15-.09c-.105-.075-.2-.15-.47-.025l-.22.1c-.13.07-.135.075-.45.09h-.325c-.28-.01-.535-.02-.815.17c-.23.16-.45.175-.615.19c-.1.01-.185.02-.23.055c-.1.085-.12.17-.12.2zm.55 4.96a.22.22 0 0 0-.19-.115c-.146 0-.21-.045-.22-.155s.02-.095.164-.01l.02.01c.09.05.14.02.175 0c.035-.015.06-.03.1 0c.085.065.05.27-.05.27m-.366.235c.05 0 .11.045.13.065c.05 0 .05-.25-.05-.255c-.115-.015-.15.19-.08.19m-.24-1.585c.05-.005.15-.025.175-.08c.03-.065.065.2-.01.215c-.08.01-.145-.09-.165-.135");
}

.eg5f20k3o {
  stop-color: var(--svg-color--ff949e, #ff949e);
}

.f_1wm2bfr {
  stop-color: var(--svg-color--abfeff, #abfeff);
}

.f5y_yf0ix {
  stop-color: var(--svg-color--131f1f, #131f1f);
}

.fsf_-254e {
  d: path("m6.535 12.304l2.37 1.9l-.54 1.88l.235-1.73z");
}

.ft5dv1b6b {
  fill: none;
}

.fu1z21blc {
  stop-color: var(--svg-color--753939, #753939);
}

.fy3x7tbar {
  stop-color: var(--svg-color--f4eae9, #f4eae9);
}

.g-5z62bsv {
  stop-color: var(--svg-color--6b6f72, #6b6f72);
}

.g0hv7h42u {
  d: path("M17.265 19.974c-.725-.02-2.07-.325-1.61-1.36c.58-1.29 1.5-1.665 2.49-1.515c.99.145.86-.89.57-.89l-.21-.02c-.51-.06-1.69-.195-2.85.55c-1.37.875-1.88.885-2.215-.27c-.34-1.16 1.545-.98 2.215-.7c.675.285 1.61-1.485 1.82-2.35c.04-.185.145-.444.26-.75c.44-1.135 1.125-2.9.05-3.7a2.9 2.9 0 0 0-1.05-.3c-.42-.064-.71-.104-.565-.42a4.5 4.5 0 0 1 1.76-1.224c.95-.295 1.15-1.17 1.045-1.52c-.11-.35-1.84-2.07-4.34-1.315a4.8 4.8 0 0 0-1.78.87c.015.145.005.33-.025.57c-.2 1.47-.74 1.63-1.275 1.71c-.345.05-.54.21-.715.35c-.1.075-.185.145-.285.185c-.225.1-.425.1-.5.09c.51.55 1.585 2.004 1.84 3.5c.33 1.964-.245 4.32-.77 6.47q-.257 1.02-.47 2.05z");
}

.gkphcdcxj {
  d: path("m17.04 16l-2.655 1.864l-.1-.1l2.395-2.015l.48-1.215l1.12-.8l-.96 1.08l-.28 1.18z");
}

.gz1v3ccid {
  stop-color: var(--svg-color--d5fdfd, #d5fdfd);
}

.h10di2y6j {
  stop-color: var(--svg-color--324242, #324242);
}

.hrnp1g9bf {
  stop-color: var(--svg-color--bec3c7, #bec3c7);
}

.htj_d2b6q {
  d: path("M5.05 8.934c.865.04 1.55.87 1.55 1.89c0 .66-.285 1.24-.725 1.58a2 2 0 0 0 .92-1.724c0-1.076-.765-1.95-1.71-1.95h-.03v.204z");
}

.ifuze0i5a {
  stop-color: var(--svg-color--176c96, #176c96);
  stop-opacity: 0.56;
}

.ixhfpnbnk {
  d: path("M10.4 19.35L5 14.525v.115l5.05 4.775l-.125.585h.24l.24-.65z");
}

.j1ae9bchu {
  stop-color: var(--svg-color--96afb4, #96afb4);
}

.j2ooxcbrl {
  stop-color: var(--svg-color--a4b9be, #a4b9be);
}

.jm6wz4bih {
  stop-color: var(--svg-color--f5dfe1, #f5dfe1);
}

.jmrlviers {
  stop-color: var(--svg-color--e3eeea, #e3eeea);
}

.jn24rbbbu {
  stop-color: var(--svg-color--d4e1e9, #d4e1e9);
}

.js94kkmqa {
  stop-color: var(--svg-color--efefef, #efefef);
}

.jxu8kdb0h {
  d: path("m19 10.52l-.165-.01c-.715 0-1.32.694-1.32 1.55c0 .86.58 1.55 1.3 1.55l.14-.006c-.625-.084-1.11-.714-1.11-1.475c0-.775.52-1.41 1.155-1.48z");
}

.kisqh2b5x {
  d: path("M5.05 12.2c.405-.15.7-.605.7-1.15c0-.55-.295-1.005-.7-1.15v.12c.34.165.58.575.58 1.05c0 .48-.24.885-.575 1.05v.075z");
}

.l52dqccet {
  stop-color: var(--svg-color--a5b8be, #a5b8be);
}

.lsctsibdo {
  stop-color: var(--svg-color--6c898d, #6c898d);
}

.m5_20ybwm {
  stop-color: var(--svg-color--555557, #555557);
}

.m7zpx_zla {
  stop-color: var(--svg-color--d6c2c4, #d6c2c4);
}

.mjcl0fb5o {
  stop-color: var(--svg-color--b3908f, #b3908f);
}

.nb2-p543p {
  d: path("m14.25 17.864l-.4.27c-1.54-2.87-1.375-6.085.65-8.57c1.11-1.355 2.69-2.325 4.475-2.405v.19a7.28 7.28 0 0 0-3.96 2.36c-1.875 2.33-2.26 4.71-.76 8.15z");
}

.nj75-ibfm {
  stop-color: var(--svg-color--5e5d5b, #5e5d5b);
}

.nxhea2bra {
  stop-color: var(--svg-color--7be8fc, #7be8fc);
}

.nz7ytzbbn {
  stop-color: var(--svg-color--9e4849, #9e4849);
}

.o4rgs-nvh {
  d: path("m13.995 18.039l-.145.095c-1.54-2.87-1.375-6.085.65-8.57c1.11-1.355 2.69-2.325 4.475-2.405v.035c-.925.08-3.19.485-4.82 3a7.46 7.46 0 0 0-.16 7.845");
}

.o8b3n_mlc {
  stop-color: var(--svg-color--f7fffd, #f7fffd);
}

.ogmq57gyo {
  stop-color: var(--svg-color--e8e2e2, #e8e2e2);
}

.p4-nmbcvt {
  d: path("m10.036 20l.23-.63l-3.56-3.115l3.34 3.16l-.12.585z");
}

.phuspdbnj {
  d: path("M9.23 7.009c-1.92.235-2.115-.825-1.97-1.38c.23-.565 1.97-.44 2.44-.645c.465-.2 1.53-.135 2.05-.235c.525-.1 1.275-.595 1.08.88c-.2 1.47-.74 1.63-1.275 1.71c-.53.075-.715.415-1 .535c-.225.1-.425.1-.5.09c.51.55 1.585 2.005 1.84 3.5c.44 2.62-.725 5.92-1.24 8.525H5.12v-.775c.36-1.725 3.645-2.15 3.88-2.925c.24-.775-1.25-.925-2.835-2.14c-1.59-1.21-1.21-5.755 0-6.185c1.205-.425 1.37.665 1.75.52c.38-.15.39-1.215.685-1.325c.295-.115 1.045 0 1.455-.08c.415-.08.47.02.785-.07s.295-.255.915-.435s-.1-.735-.525-.95c-.34-.17-.83.4-1.03.7c-.46 0-.22.685-.97.685");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q920b_bde {
  d: path("m19 17.205l-.636.24l-.545 1.33l.675-1.125l.505-.235z");
}

.quqi49b8b {
  d: path("m14.335 17.81l2.45-1.971l.46-1.24l.82-.62l.215-.245l-1.12.8l-.48 1.215l-2.395 2.01z");
}

.r3alx330p {
  stop-color: var(--svg-color--f3e8e4, #f3e8e4);
}

.r5nd0jokb {
  d: path("M9.035 14.21L6.47 12.24l2.13 2.115l-.37 2.73l.8-2.875z");
}

.rezxhqr5u {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.025 13.49l.185-1.295l2.265-1.315l.115.35z");
}

.s3x0-rb2d {
  stop-color: var(--svg-color--dffdff, #dffdff);
}

.ssx3e5b6i {
  fill: var(--svg-color--4afffe, #4afffe);
  d: path("M13.778 13.126c.339.411 1.208.22 1.94-.427c.734-.646 1.053-1.504.714-1.915c-.34-.411-1.208-.22-1.941.427s-1.053 1.504-.713 1.915");
}

.su4r9jbcc {
  stop-color: var(--svg-color--d2a3a3, #d2a3a3);
}

.tb_q_pbom {
  stop-color: var(--svg-color--072230, #072230);
  stop-opacity: 0.65;
}

.trzkvt_lc {
  stop-color: var(--svg-color--a6a9a9, #a6a9a9);
}

.u01m3lmub {
  stop-color: var(--svg-color--514f50, #514f50);
}

.u4afi8bui {
  stop-color: var(--svg-color--686264, #686264);
}

.uabxjjb7w {
  stop-color: var(--svg-color--93b6b8, #93b6b8);
}

.ub-6xfjiy {
  stop-color: var(--svg-color--02849d, #02849d);
  stop-opacity: 0.34;
}

.v6pb5cb6p {
  stop-color: var(--svg-color--ebd8d2, #ebd8d2);
}

.vp11k1byg {
  stop-color: var(--svg-color--886e71, #886e71);
}

.w65tc8z-r {
  fill-rule: evenodd;
  d: path("M13.614 8c-.115.034-.105.15-.09.2v.01l.01.02s.015 0 .05-.02l.015-.006c.08-.035.12-.035.175.09c.035.07-.014.09-.084.115a.5.5 0 0 0-.166.1c-.074.07-.044.1-.004.135c.024.025.05.05.05.1l-.006.045c-.014.085-.02.15.09.27c.1.105.085.14.04.225l-.04.075c-.02.05-.04.065-.055.075c-.025.02-.035.025 0 .25c.04.25.1.26.165.275c.036.01.066.015.1.045c.105.09.04.12-.035.075s-.15.05-.11.135c.025.05.075.065.12.08c.04.01.075.025.066.055c-.01.035-.05.025-.085.02c-.04-.01-.08-.02-.1.015c-.03.07.064.19.184.135c.04-.02.115-.075.2-.14c.19-.135.435-.32.54-.3c.095.02.115.06.15.12c.02.04.05.09.1.15c.14.16.175.24.11.315c-.05.065-.06.25-.055.34a3 3 0 0 0 .73-.36c.035-.055.02-.105.005-.155a.24.24 0 0 1-.005-.14c.01-.045.07-.05.125-.06c.085-.015.17-.03.115-.165c-.075-.165-.12-.17-.22-.185c-.035-.005-.08-.01-.13-.025c-.11-.035-.155-.07-.205-.1a.5.5 0 0 0-.145-.08c-.065-.025-.1-.115-.135-.215c-.05-.13-.1-.275-.245-.34c-.17-.075-.2-.225-.23-.35a.5.5 0 0 0-.05-.145c-.035-.05-.03-.115-.025-.18c0-.07.01-.135-.04-.18a.4.4 0 0 0-.165-.05c-.08-.015-.175-.03-.25-.105c-.08-.08 0-.155.07-.215c.04-.04.08-.075.06-.1c-.024-.045-.05-.02-.085.02l-.075.08c-.1.08-.12-.145-.12-.27c0-.075.015-.07.05-.055c.015.005.04.015.07.01c.075-.01.066-.055 0-.11c-.03-.025-.05-.01-.074.005c-.035.025-.08.05-.166-.03c-.145-.135.065-.27.075-.155c.01.11.065.18.13.09c.026-.04 0-.085-.014-.13c-.03-.06-.05-.11.08-.1c.23.025.45.04.64-.02c.1-.025.164-.095.22-.15c.06-.06.11-.115.174-.105c.1.005.23-.045.28-.07c.07-.045.07-.07.07-.1c0-.04 0-.08.125-.16c.305-.195.375-.36.425-.475l.025-.05c.04-.085.08-.09.15-.095c.025 0 .05 0 .085-.01c.05-.005.08 0 .105.005c.035.01.06.015.125-.05c.11-.1.175-.19.165-.325c-.015-.135-.065-.28-.34-.575c-.2-.215-.34-.18-.47-.145c-.05.01-.095.025-.14.025a.8.8 0 0 1-.18-.03a.5.5 0 0 0-.34-.005c-.105.04-.175.05-.24.065s-.12.025-.205.06a.8.8 0 0 1-.24.035c-.155.015-.325.025-.414.13c-.095.115-.17.12-.286.13c-.055.005-.12.01-.2.03c-.25.055-.34.11-.185.38c.105.195.095.215.05.285c-.01.03-.034.07-.05.135c-.065.21.1.36.185.29c.035-.03.05-.055.055-.075c.01-.025.015-.035.06-.035c.05 0 .09-.05.13-.11c.025-.04.05-.08.09-.105c.05-.04-.01-.08-.08-.125c-.05-.035-.11-.075-.14-.125c-.065-.11-.02-.235.066-.235c.05 0 .05.05.05.1c-.006.035-.006.07.02.07c.05 0 .13-.1.14-.34c.004-.16.2-.195.344-.22a.4.4 0 0 0 .15-.05c.05-.03.21-.05.38-.075c.185-.025.375-.05.43-.09c.05-.035.075-.03.125-.015c.065.015.165.045.4.015c.41-.06.605.495.64.605c.02.08-.05.1-.13.13l-.1.04c-.065.035-.07.015-.07-.005c0-.015-.005-.03-.03-.03c-.03 0-.035.02-.05.055a.3.3 0 0 1-.05.115c-.035.065-.065.08-.1.1s-.07.035-.115.08a.6.6 0 0 0-.085.1a.24.24 0 0 1-.13.115c-.065.025-.075.055-.08.095a.13.13 0 0 1-.05.085a1 1 0 0 0-.185.17l-.1.1c-.04.035-.08.005-.125-.02c-.04-.03-.09-.06-.15-.05c-.055.01-.065.04-.075.07c-.01.035-.025.075-.1.11a.2.2 0 0 0-.1.1c-.02.035-.03.065-.09.08c-.07.02-.08-.01-.09-.05a.17.17 0 0 0-.05-.1c-.07-.05-.08-.04-.135-.005l-.075.045l-.064.035c-.066.04-.085.05-.196 0c-.1-.05-.25.075-.35.165l-.105.08c-.06.03-.145 0-.23-.04l-.11-.04c-.12-.035-.12.135.046.16c.13.015.204.1.23.145c-.03.01-.056 0-.085-.005c-.04-.015-.08-.025-.116.04c-.03.07.01.07.055.075c.045 0 .095 0 .1.06c.005.07.07.1.136.135a.3.3 0 0 1 .094.065l.015.02c.05.065.11.13-.015.17m.78 1.15c.19-.066.275.134.295.25l.02.334c-.18.08-.585.235-.75.2c-.204-.045-.23-.37-.03-.44l.135-.04c.116-.035.18-.05.15-.1c-.05-.07-.06-.13.18-.205m.85 1.38c-.065.014-.195.014-.185-.1c.01-.15.12-.15.185-.09c.065.054.085.16 0 .19m-.25-.56c.095.034.14.014.15 0c.21-.1.305-.08.35.034c.02.05.04.075.06.095s.035.04.05.095c.02.1-.1.045-.21-.035c-.085-.065-.15-.05-.26-.035l-.1.015c-.185.02-.16-.215-.04-.17M13.73 6.01c-.06.02-.17.064-.116.09c.025.014.05.02.066.02c.034.01.054.014.064.05c.01.05.15-.036.15-.07c0-.026-.11-.07-.165-.09m.11.854c0 .035-.03.07-.066.07a.065.065 0 0 1-.064-.07c0-.035.03-.065.064-.065c.035 0 .065.03.065.065m1.95 2.71c-.1-.025-.3-.265-.386-.38c-.02-.06-.04-.155.055-.06c.12.125.22.17.415.1c.2-.065.335-.04.5.115c.165.16-.165.385-.315.37a.23.23 0 0 1-.16-.075c-.03-.025-.06-.055-.11-.07m-.056-.17c-.05-.08.1-.06.14-.055h.01c.03.07.09.115.14.15s.085.06.055.085c-.035.04-.065.02-.105-.01a.4.4 0 0 0-.09-.045c-.1-.035-.1-.035-.15-.125");
}

.w90bhlbxp {
  stop-color: var(--svg-color--b81214, #b81214);
}

.x1h0_9f7j {
  stop-color: var(--svg-color--d2d7dd, #d2d7dd);
}

.xhz0a0yat {
  stop-color: var(--svg-color--6c0808, #6c0808);
  stop-opacity: 0.57;
}

.xm9oltbko {
  stop-color: var(--svg-color--d2d8de, #d2d8de);
}

.ymyprzg5j {
  d: path("M6.11 6.628c1.714.11 2.84.765 3.57 1.63a5.8 5.8 0 0 1 1.264 5.165l-.01.04l.415.24l-1.48 3.52l-.08.225h.01l1.715-3.76l-.425-.21c.335-1.365.175-3.45-1.2-5.14a4.55 4.55 0 0 0-3.78-1.71");
}

.yr2tuwarl {
  fill: var(--svg-color--fdfefc, #fdfefc);
  d: path("M7.48 11.094V10.1l2.805 2.07l-.295.235l-2.51-1.315z");
}

.yxe7vqbgs {
  d: path("M9.895 8.34C8.98 7.203 7.51 6.39 5.285 6.693c3.675-.18 5.925 3.43 5.26 6.5l-3.61-1.81l4.2 2.43L9.75 17.55l1.765-3.86l-.425-.21a6.1 6.1 0 0 0-1.2-5.14z");
}

.yyhdiub6i {
  stop-color: var(--svg-color--b1f7fc, #b1f7fc);
}

.znk-7xb2j {
  stop-color: var(--svg-color--8a7f79, #8a7f79);
}

</style>
