<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGpQHORbxQ)" class="h899bp0wb"/><path fill="url(#SVGuv4Tib1A)" class="ievduwb8m"/><path fill="url(#SVG9P1pC5tJ)" class="wujk-uzfh"/><path fill="url(#SVG7UNK5b0k)" class="hy68imbwq"/><path fill="url(#SVGJ4pOJc5l)" class="bwv79fqkm"/><path fill="url(#SVGVmNvDcGr)" class="cjtfbo4fn"/><path fill="url(#SVGj5Cr9bWD)" class="vtxwvbp7l"/><path fill="url(#SVGIyc7AbOo)" class="tf161cc_v"/><path fill="url(#SVGq07ytdaI)" class="sihh70ysz"/><path fill="url(#SVGgspBhbji)" class="gr6m-qbrx"/><path fill="url(#SVGClizsbKT)" class="x4g19vl7h"/><path fill="url(#SVGfS3Lld2H)" class="p7s5ondwr"/><path fill="url(#SVGVYbTqcGI)" class="xhybnyyha"/><path fill="url(#SVGjTmFGb4i)" class="sf68w6blf"/><path fill="url(#SVGLcrFHcCX)" class="sf68w6blf"/><path fill="url(#SVGxTwCybcg)" class="lguo-3dov"/><path fill="url(#SVGGBQ27cmg)" class="njc56bcnq"/><path class="p1f1h8boz"/><defs><linearGradient id="SVGpQHORbxQ" x1="8.61" x2="21.2" y1="3.522" y2="9.304" gradientUnits="userSpaceOnUse"><stop offset=".339" class="nhgbnybxn"/><stop offset=".948" class="xo05v3b5o"/></linearGradient><linearGradient id="SVGuv4Tib1A" x1="4.17" x2="20.755" y1="3.001" y2="14.631" gradientUnits="userSpaceOnUse"><stop class="ymbcisyhw"/><stop offset="1" class="xzjosgb6g"/></linearGradient><linearGradient id="SVG9P1pC5tJ" x1="-2.481" x2="-3.115" y1="11.141" y2="22.14" gradientUnits="userSpaceOnUse"><stop class="q6oxmbcor"/><stop offset=".314" class="por0vwb0s"/><stop offset=".49" class="f_4b8v52r"/><stop offset=".688" class="ofaosnmdk"/><stop offset="1" class="o2rsw2piw"/></linearGradient><linearGradient id="SVG7UNK5b0k" x1="15.075" x2="19.88" y1="3.562" y2="5.278" gradientUnits="userSpaceOnUse"><stop class="qm6en0b7i"/><stop offset="1" class="pe_ir7b_l"/></linearGradient><linearGradient id="SVGJ4pOJc5l" x1="15.388" x2="20.878" y1="6.527" y2="7.276" gradientUnits="userSpaceOnUse"><stop class="oob_bt5kk"/><stop offset="1" class="tt26zlqda"/></linearGradient><linearGradient id="SVGVmNvDcGr" x1="5.183" x2="9.839" y1="9.301" y2="24.575" gradientUnits="userSpaceOnUse"><stop class="pfcyh6bhh"/><stop offset="1" class="m6lpkqogp"/></linearGradient><linearGradient id="SVGj5Cr9bWD" x1="10.512" x2="13.726" y1="7.057" y2="17.164" gradientUnits="userSpaceOnUse"><stop class="sigu6q_6b"/><stop offset=".469" class="q2vz7-5_m"/><stop offset=".891" class="ofaosnmdk"/><stop offset="1" class="p6ex73b2y"/></linearGradient><linearGradient id="SVGIyc7AbOo" x1="12.406" x2="8.119" y1="8.574" y2="18.454" gradientUnits="userSpaceOnUse"><stop class="cyifvkixu"/><stop offset=".469" class="q2vz7-5_m"/><stop offset="1" class="ofaosnmdk"/></linearGradient><linearGradient id="SVGq07ytdaI" x1="6.532" x2="21.489" y1="7.57" y2="16.192" gradientUnits="userSpaceOnUse"><stop class="mkybuwbwx"/><stop offset="1" class="cyifvkixu"/></linearGradient><linearGradient id="SVGgspBhbji" x1="12.002" x2="12.002" y1="2.999" y2="21.002" gradientUnits="userSpaceOnUse"><stop class="jh3o22b4p"/><stop offset="1" class="xzjosgb6g"/></linearGradient><linearGradient id="SVGClizsbKT" x1="8.781" x2="10.198" y1="4.262" y2="21.15" gradientUnits="userSpaceOnUse"><stop class="sf2eu3bbo"/><stop offset=".214" class="m-hpc-68z"/><stop offset=".464" class="ho0yjy8zp"/><stop offset=".688" class="e8rkwzbgp"/><stop offset=".865" class="f3iir7bex"/><stop offset=".974" class="tixjhqbsd"/></linearGradient><linearGradient id="SVGfS3Lld2H" x1="5.115" x2="30.267" y1="11.248" y2="12.041" gradientUnits="userSpaceOnUse"><stop class="txoqg2b0p"/><stop offset="1" class="nn_xi--wp"/></linearGradient><linearGradient id="SVGVYbTqcGI" x1="17.075" x2="15.688" y1="29.584" y2="1.372" gradientUnits="userSpaceOnUse"><stop class="iwsw1wbvv"/><stop offset="1" class="w6p0sac3k"/></linearGradient><linearGradient id="SVGjTmFGb4i" x1="18.077" x2="8.979" y1="9.628" y2="14.612" gradientUnits="userSpaceOnUse"><stop class="m74uv_ccd"/><stop offset="1" class="t7uyutbrm"/></linearGradient><linearGradient id="SVGLcrFHcCX" x1="4.482" x2="12.235" y1="4.914" y2="7.717" gradientUnits="userSpaceOnUse"><stop class="p-wftxb3u"/><stop offset="1" class="oi9ml243e"/></linearGradient><linearGradient id="SVGxTwCybcg" x1="7.425" x2="8.079" y1="11.291" y2="23.711" gradientUnits="userSpaceOnUse"><stop class="q6oxmbcor"/><stop offset=".314" class="por0vwb0s"/><stop offset=".49" class="f_4b8v52r"/><stop offset=".688" class="ofaosnmdk"/><stop offset="1" class="trtpgbb3m"/></linearGradient><linearGradient id="SVGGBQ27cmg" x1="3.906" x2="11.039" y1="9.407" y2="20.221" gradientUnits="userSpaceOnUse"><stop class="t7dn-obdm"/><stop offset="1" class="pb4k9xbzv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:crv" /></template>
<style>
.bwv79fqkm {
  d: path("M4.32 7.273c-.177-.764-.074-1.446 0-1.692c.175-.67 1.055-2.093 3.165-2.425s4-.052 4.68.317c.648.434.368 1.755-.947 1.382c-1.916-.553-2.212.178-2.054 1.185c.426 2.228.177 3.72 0 4.187c0 0-.573 1.442-1.047.988c-.81-.81-1.56-.652-2.39-.435c-.663.174-.863-.296-.88-.553c-.102-.666-.35-2.19-.528-2.954");
}

.cjtfbo4fn {
  d: path("M6.175 3.55c-1.505.718-.961 3.52-.492 4.906c.511-.32 2.077-.193 2.557.319c-.716-4.066.976-5.694 1.488-5.662c0 0-.84-.09-1.425-.04c-.701.04-1.456.157-2.128.478");
}

.cyifvkixu {
  stop-color: var(--svg-color--f1fc06, #f1fc06);
}

.e8rkwzbgp {
  stop-color: var(--svg-color--36ffc1, #36ffc1);
}

.f_4b8v52r {
  stop-color: var(--svg-color--87ff70, #87ff70);
}

.f3iir7bex {
  stop-color: var(--svg-color--00a0ff, #00a0ff);
}

.ft5dv1b6b {
  fill: none;
}

.gr6m-qbrx {
  d: path("M19.075 10.407c-1.348.257-1.235-.309-1.011-.623c.715-.877 1.938-.365 2.46 0c.08.1-.1.367-1.449.623");
}

.h899bp0wb {
  d: path("M20.5 12.235c-1.08 2.79-5.696 3.605-10.311 1.819c-4.35-1.684-8.362-8.56-2.938-10.84c1.926-.433 4.388-.22 6.85.733c4.615 1.786 7.48 5.497 6.4 8.288");
}

.ho0yjy8zp {
  stop-color: var(--svg-color--a4ff53, #a4ff53);
}

.hy68imbwq {
  d: path("M3.638 7.322c.107-.861.647-1.897.99-2.375l6.133-1.852c6.284 1.042 4.818 3.592.155 3.153c-1.436-.135-.743 1.2-.659 2.434c.389 2.62-.202 2.925-1.115 4.277c-.321-.66-1.032-1.91-2.3-1.995c-1.014-.067-2 1.217-2.214 1.69c-.056-.05-.247-.906-.355-1.257c-.562-1.173-.827-2.531-.635-4.075");
}

.ievduwb8m {
  d: path("M15.165 5.028c-1.062-.195-1.132 1.171-.987 1.935c2.83 1.117 3.778 2.78 3.848 2.886c1.293-1.1 2.609.129 2.726 1.068c-.14-3.049-4.142-5.623-5.587-5.89");
}

.iwsw1wbvv {
  stop-color: var(--svg-color--dffd18, #dffd18);
}

.jh3o22b4p {
  stop-color: var(--svg-color--ffd701, #ffd701);
}

.lguo-3dov {
  d: path("M10.022 7.628c.728 2.349-.188 4.399-.794 5.191c.95 2.212.262 4.393.262 5.013s1.323.455 1.53 0c.763-2.368.72-6.566-.998-10.204");
}

.m-hpc-68z {
  stop-color: var(--svg-color--deff19, #deff19);
}

.m6lpkqogp {
  stop-color: var(--svg-color--fa0f01, #fa0f01);
}

.m74uv_ccd {
  stop-color: var(--svg-color--14f3e6, #14f3e6);
}

.mkybuwbwx {
  stop-color: var(--svg-color--ffc100, #ffc100);
}

.nhgbnybxn {
  stop-color: var(--svg-color--ff7301, #ff7301);
}

.njc56bcnq {
  d: path("m5.137 12.863l-.487-.198c.135-.42.805-1.67 2.153-1.74c-.427.123-1.48 1.115-1.666 1.938");
}

.nn_xi--wp {
  stop-color: var(--svg-color--ffdb00, #ffdb00);
}

.o2rsw2piw {
  stop-color: var(--svg-color--00beff, #00beff);
}

.ofaosnmdk {
  stop-color: var(--svg-color--1cffdb, #1cffdb);
}

.oi9ml243e {
  stop-color: var(--svg-color--0001fc, #0001fc);
  stop-opacity: 0;
}

.oob_bt5kk {
  stop-color: var(--svg-color--fa0f00, #fa0f00);
}

.p-wftxb3u {
  stop-color: var(--svg-color--09d3f3, #09d3f3);
}

.p1f1h8boz {
  fill: var(--svg-color--f4ba0c, #f4ba0c);
  d: path("M6.916 12.907c-1.01.269-1.916-.028-2.243-.21a3.8 3.8 0 0 0-.41 1.3c1.403.421 3.946-.473 5.042-.972l-.255-.545c-.29.03-1.124.158-2.134.427");
}

.p6ex73b2y {
  stop-color: var(--svg-color--00dcfe, #00dcfe);
}

.p7s5ondwr {
  d: path("M6.624 12.953c-.945.175-1.726-.122-1.998-.292c.257-.52.93-1.649 2.202-1.736c1.15-.078 1.885.85 2.216 1.55c-.481-.039-1.475.303-2.42.478");
}

.pb4k9xbzv {
  stop-color: var(--svg-color--f4bb0c, #f4bb0c);
}

.pe_ir7b_l {
  stop-color: var(--svg-color--ff7300, #ff7300);
}

.pfcyh6bhh {
  stop-color: var(--svg-color--a80000, #a80000);
}

.por0vwb0s {
  stop-color: var(--svg-color--d4ff23, #d4ff23);
}

.q2vz7-5_m {
  stop-color: var(--svg-color--7aff7d, #7aff7d);
}

.q6oxmbcor {
  stop-color: var(--svg-color--ff9100, #ff9100);
}

.qm6en0b7i {
  stop-color: var(--svg-color--ff4e00, #ff4e00);
}

.sf2eu3bbo {
  stop-color: var(--svg-color--ffa300, #ffa300);
}

.sf68w6blf {
  d: path("M8.055 21c1.618.035 2.648-2.088 2.96-3.155l-1.532-.119c-.139.62-.846 1.814-2.174 1.966c-1.411.162-2.462-1.612-2.789-2.505a.3.3 0 0 1-.131.075C4.82 18.602 6.03 20.955 8.055 21");
}

.sigu6q_6b {
  stop-color: var(--svg-color--ffe600, #ffe600);
}

.sihh70ysz {
  d: path("M18.035 9.868c-.692-2.603-7.15-4.015-7.812-3.557c-.396.273-.234 1.329 0 1.924c3.201-.314 6.203 1.251 7.213 2.052c.16-.037.54-.326.6-.419");
}

.t7dn-obdm {
  stop-color: var(--svg-color--ff4e01, #ff4e01);
}

.t7uyutbrm {
  stop-color: var(--svg-color--0040ff, #0040ff);
}

.tf161cc_v {
  d: path("M10.315 8.218c-.282.119.643 2.428.942 3.583c4.644-.348 6.192-1.5 6.21-1.5c-2.603-2.157-6.798-2.232-7.152-2.083");
}

.tixjhqbsd {
  stop-color: var(--svg-color--0064ff, #0064ff);
}

.trtpgbb3m {
  stop-color: var(--svg-color--00d8ff, #00d8ff);
}

.tt26zlqda {
  stop-color: var(--svg-color--ff6e01, #ff6e01);
}

.txoqg2b0p {
  stop-color: var(--svg-color--ff8a01, #ff8a01);
}

.vtxwvbp7l {
  d: path("M18.095 9.79c-1.19 1.328-5.078 1.871-6.873 1.977c.374 1.795.035 4.528-.182 5.67c2.314-.731 7.128-2.231 7.875-2.384c.935-.19 2.079-1.659 1.888-3.795c-.19-2.135-1.945-2.268-2.708-1.467");
}

.w6p0sac3k {
  stop-color: var(--svg-color--fdad12, #fdad12);
}

.wujk-uzfh {
  d: path("M4.518 17.195c-.742-2.284-.061-4.295.373-5.014c-.39-1.803-1.119-5.422-1.142-5.4c-1.28 4.507-.123 8.876.643 10.488z");
}

.x4g19vl7h {
  d: path("M7.363 19.73c1.564-.123 2.678-2.18 2.488-4.596s-1.61-4.274-3.175-4.151c-1.564.122-2.678 2.18-2.488 4.595c.19 2.416 1.611 4.274 3.175 4.151");
}

.xhybnyyha {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M6.624 12.953c-.945.175-1.726-.122-1.998-.292c.257-.52.93-1.649 2.202-1.736c1.15-.078 1.885.85 2.216 1.55c-.481-.039-1.475.303-2.42.478");
}

.xo05v3b5o {
  stop-color: var(--svg-color--ffdd01, #ffdd01);
}

.xzjosgb6g {
  stop-color: var(--svg-color--ffe601, #ffe601);
}

.ymbcisyhw {
  stop-color: var(--svg-color--ff8101, #ff8101);
}

</style>
