<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGGNuHoiPd)" class="c1r_s2rmp"/><path fill="url(#SVGqOvEZcyF)" class="nx97vtbsl"/><path class="m6-810w1l"/><path class="re1uklbnh"/><path fill="url(#SVGHhZBHdcl)" class="b8jgyjbbb"/><path fill="url(#SVGJ0l5bczm)" class="ff6nq3b5j"/><path fill="url(#SVGbiIflcZR)" class="o1sr77egk"/><path fill="url(#SVGJs1xHdax)" class="txjovrb-z"/><path fill="url(#SVGsmEwEbya)" class="cq3vc58nw"/><path class="wtl3ii3lq"/><path class="z2knq8z3y"/><path fill="url(#SVGqdYEjdWT)" class="j9aefewkh"/><path fill="url(#SVGEL5kBdnW)" class="j8ncxsbfr"/><path fill="url(#SVGr3QlGchJ)" class="zclfcabzu"/><path fill="url(#SVG1bZpbbjB)" class="v35tnxrhg"/><path fill="url(#SVG451TCd2u)" class="jt7vfwbkb"/><path class="eempfhbef"/><path class="umxypt-8g"/><path fill="url(#SVGtv1glbzv)" class="e39_0wbzz"/><path class="khv6shzoo"/><path class="zgx1r5b0h"/><path fill="url(#SVGyUkUtefb)" class="j6fit4cth"/><path class="iyq4i8hze"/><path fill="url(#SVGk8nv5cgA)" class="ww8v6oywb"/><path fill="url(#SVGNP0uIdPQ)" class="z7uaz7boh"/><path fill="url(#SVGJ68Nmbxx)" class="q1rkk0lqr"/><path fill="url(#SVGccGRtbEx)" clip-rule="evenodd" class="uouse2bfu"/><defs><linearGradient id="SVGGNuHoiPd" x1="16.293" x2="12.508" y1="11.997" y2="11.997" gradientUnits="userSpaceOnUse"><stop offset=".42" class="pzq9w9r-z"/><stop offset=".56" class="eztjh12zh"/><stop offset=".64" class="j1z_bd6zn"/><stop offset=".89" class="pah8wbbim"/><stop offset="1" class="wu31gdcmy"/></linearGradient><linearGradient id="SVGqOvEZcyF" x1="16.738" x2="12.475" y1="10.519" y2="10.519" gradientUnits="userSpaceOnUse"><stop offset=".27" class="g0lzk0d0p"/><stop offset=".42" class="dyly8dirg"/><stop offset=".67" class="llsznpb4g"/></linearGradient><linearGradient id="SVGHhZBHdcl" x1="5.113" x2="5.113" y1="13.568" y2="17.684" gradientUnits="userSpaceOnUse"><stop class="lc1cjybsp"/><stop offset="1" class="bz-cjybhr"/></linearGradient><linearGradient id="SVGJ0l5bczm" x1="4.223" x2="4.223" y1="10.835" y2="14.165" gradientUnits="userSpaceOnUse"><stop class="i247-56py"/><stop offset="1" class="dfwpml94h"/></linearGradient><linearGradient id="SVGbiIflcZR" x1="6.372" x2="6.372" y1="11.839" y2="17.684" gradientUnits="userSpaceOnUse"><stop class="jga12jetw"/><stop offset="1" class="k3ekmu1zq"/></linearGradient><linearGradient id="SVGJs1xHdax" x1="4.601" x2="4.601" y1="14.237" y2="17.51" gradientUnits="userSpaceOnUse"><stop class="odhqnn32q"/><stop offset="1" class="q6r8l7blc"/></linearGradient><linearGradient id="SVGsmEwEbya" x1="5.479" x2="5.602" y1="9.339" y2="11.271" gradientUnits="userSpaceOnUse"><stop offset=".08" class="xsdc5kbga"/><stop offset=".15" class="o2s8vwbmy"/><stop offset=".42" class="jr_2a2mie"/></linearGradient><linearGradient id="SVGqdYEjdWT" x1="5.989" x2="5.193" y1="9.893" y2="10.646" gradientUnits="userSpaceOnUse"><stop class="irk2pjhja"/><stop offset=".32" class="ia3ol-mxd"/><stop offset=".53" class="fgrimybvd"/><stop offset=".72" class="b2dyaabkp"/><stop offset="1" class="e9_yoi2gg"/></linearGradient><linearGradient id="SVGEL5kBdnW" x1="3.669" x2="4.715" y1="11.068" y2="11.129" gradientUnits="userSpaceOnUse"><stop class="l7aydfiyl"/><stop offset="1" class="cvbkfeb3r"/></linearGradient><linearGradient id="SVGr3QlGchJ" x1="6.582" x2="8.159" y1="11.04" y2="11.191" gradientUnits="userSpaceOnUse"><stop class="l7aydfiyl"/><stop offset="1" class="cvbkfeb3r"/></linearGradient><linearGradient id="SVG1bZpbbjB" x1="3.849" x2="3.583" y1="9.694" y2="11.239" gradientUnits="userSpaceOnUse"><stop offset=".31" class="g1b6akb_k"/><stop offset="1" class="n_77cjbij"/></linearGradient><linearGradient id="SVG451TCd2u" x1="10.049" x2="10.049" y1="9.576" y2="13.896" gradientUnits="userSpaceOnUse"><stop offset=".09" class="oli1qbc6g"/><stop offset=".26" class="rholo2byn"/><stop offset=".43" class="affxs5b2m"/><stop offset=".61" class="qfw73ibsw"/><stop offset=".76" class="odgoljv5n"/><stop offset=".93" class="rzwbe1teq"/></linearGradient><linearGradient id="SVGtv1glbzv" x1="19.048" x2="19.048" y1="9.576" y2="13.896" gradientUnits="userSpaceOnUse"><stop offset=".09" class="oli1qbc6g"/><stop offset=".26" class="rholo2byn"/><stop offset=".43" class="affxs5b2m"/><stop offset=".61" class="qfw73ibsw"/><stop offset=".76" class="odgoljv5n"/><stop offset=".93" class="rzwbe1teq"/></linearGradient><linearGradient id="SVGyUkUtefb" x1="12.947" x2="12.947" y1="14.567" y2="17.485" gradientUnits="userSpaceOnUse"><stop offset=".54" class="g_f1mcawx"/><stop offset=".66" class="uik8v9b0b"/></linearGradient><linearGradient id="SVGk8nv5cgA" x1="9.395" x2="9.395" y1="14.843" y2="17.211" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><linearGradient id="SVGNP0uIdPQ" x1="11.525" x2="11.525" y1="14.843" y2="17.211" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><linearGradient id="SVGJ68Nmbxx" x1="14.133" x2="14.133" y1="14.843" y2="17.211" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient><linearGradient id="SVGccGRtbEx" x1="16.742" x2="16.742" y1="14.843" y2="17.211" gradientUnits="userSpaceOnUse"><stop class="jr_d1qboy"/><stop offset=".92" class="rdk0dpevl"/><stop offset=".97" class="lg92gcczw"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fara" /></template>
<style>
.affxs5b2m {
  stop-color: var(--svg-color--ccc8c4, #ccc8c4);
}

.b2dyaabkp {
  stop-color: var(--svg-color--6c0425, #6c0425);
}

.b8jgyjbbb {
  d: path("m6.364 16.452l.294-1.819c-.218-.36-.768-1.212-1.208-1.212s-1.137.54-1.426.739h-.455l-.005.01a4.88 4.88 0 0 1 2.051 3.305q.016.106.048.209c.246-.299.488-.744.706-1.232z");
}

.bz-cjybhr {
  stop-color: var(--svg-color--b9b1ab, #b9b1ab);
}

.c1r_s2rmp {
  d: path("M12.475 13.707V9.453l.46.114l.61 1.151h3.06l-.17 1.014a2.56 2.56 0 0 0-1.094-.303c-.446 0-.839.288-.981.435v1.383l-.303.242l-1.26.407z");
}

.cq3vc58nw {
  d: path("M5.445 9.462a5.5 5.5 0 0 1-2.415-.095c-.161.753.374 1.582.663 1.904c.08-.137.293-.412.497-.412c.2 0 .422.275.507.412c.066-.118.332-.35.872-.35c.535 0 .828.208.909.312c.118-.151.455-.46.824-.46c.46 0 .753.342.91.498c-.105-2.155-1.388-2.056-2.767-1.81");
}

.cvbkfeb3r {
  stop-color: var(--svg-color--c99f4b, #c99f4b);
}

.dfwpml94h {
  stop-color: var(--svg-color--a4a5a7, #a4a5a7);
}

.dyly8dirg {
  stop-color: var(--svg-color--88857c, #88857c);
}

.e39_0wbzz {
  d: path("M17.21 10.675V9.576l3.401.157l.275 2.326l-.123 1.653c-.142-.053-.663-.161-1.596-.161c-.929 0-1.502.232-1.672.345l-.285-.27V12.06c.052-.128.285-.417.81-.555c.659-.17.962-.35.962-.568c0-.213-.118-.417-.692-.417c-.46 0-.758.208-.852.313z");
}

.e9_yoi2gg {
  stop-color: var(--svg-color--fd67b4, #fd67b4);
}

.eempfhbef {
  fill: var(--svg-color--eeeae9, #eeeae9);
  d: path("M9.158 9.158c-.587 0-.876.275-.947.412l2.146.616l1.198 2.761l.213.725l.232-.204v-3.287c0-.597-.62-.933-.928-1.023z");
}

.eztjh12zh {
  stop-color: var(--svg-color--f7f4ef, #f7f4ef);
}

.ff6nq3b5j {
  d: path("M4.507 10.835c.17.308.389.862.389 1.497c0 .781-.588 1.549-.872 1.833H3.55l.176-.251c.355-.498.682-1.052.696-1.639c.01-.265.005-.54-.175-.815c0-.038.019-.07.042-.113c.052-.095.133-.232.08-.512h.143z");
}

.fgrimybvd {
  stop-color: var(--svg-color--73001e, #73001e);
}

.ft5dv1b6b {
  fill: none;
}

.g_f1mcawx {
  stop-color: var(--svg-color--281c1e, #281c1e);
}

.g0lzk0d0p {
  stop-color: var(--svg-color--f3f3f3, #f3f3f3);
}

.g1b6akb_k {
  stop-color: var(--svg-color--6b3b04, #6b3b04);
}

.i247-56py {
  stop-color: var(--svg-color--7c8280, #7c8280);
}

.ia3ol-mxd {
  stop-color: var(--svg-color--cb7493, #cb7493);
}

.irk2pjhja {
  stop-color: var(--svg-color--eca0b2, #eca0b2);
}

.iyq4i8hze {
  fill: var(--svg-color--2c1f18, #2c1f18);
  d: path("M7.454 16.363v-.9l.89-.9h9.208l.89.9v.9l-1.221 1.123H8.676z");
}

.j1z_bd6zn {
  stop-color: var(--svg-color--af7239, #af7239);
}

.j6fit4cth {
  d: path("m7.263 15.377l1-1.009h9.369l.999 1.01v1.074l-1.34 1.232H8.603l-1.34-1.232z");
}

.j8ncxsbfr {
  d: path("M4.715 11.243c.01-.27-.066-.663-.454-.663c-.332 0-.512.36-.588.673l.015.018c.085-.118.298-.35.502-.35c.199 0 .421.237.506.35l.02-.023z");
}

.j9aefewkh {
  d: path("m6.316 10.22l-.786-.587l-.635.767l.8.654z");
}

.jga12jetw {
  stop-color: var(--svg-color--e8e8ed, #e8e8ed);
}

.jr_2a2mie {
  stop-color: var(--svg-color--8c5012, #8c5012);
}

.jr_d1qboy {
  stop-color: var(--svg-color--d7922b, #d7922b);
}

.jt7vfwbkb {
  d: path("M8.21 10.675V9.576l3.402.157l.275 2.326l-.123 1.653c-.143-.053-.664-.161-1.597-.161c-.928 0-1.501.232-1.672.345l-.284-.27V12.06c.052-.128.284-.417.81-.555c.658-.17.961-.35.961-.568c0-.213-.118-.417-.691-.417c-.46 0-.758.208-.853.313z");
}

.k3ekmu1zq {
  stop-color: var(--svg-color--f3f5ea, #f3f5ea);
}

.khv6shzoo {
  fill: var(--svg-color--eeeae9, #eeeae9);
  d: path("M18.158 9.158c-.588 0-.876.275-.948.412l2.146.616l1.199 2.761l.213.725l.232-.204v-3.287c0-.597-.62-.933-.929-1.023z");
}

.l7aydfiyl {
  stop-color: var(--svg-color--896322, #896322);
}

.lc1cjybsp {
  stop-color: var(--svg-color--bfbfbf, #bfbfbf);
}

.lg92gcczw {
  stop-color: var(--svg-color--dab15f, #dab15f);
}

.llsznpb4g {
  stop-color: var(--svg-color--cecac7, #cecac7);
}

.m6-810w1l {
  fill: var(--svg-color--bcbbb9, #bcbbb9);
  d: path("M12.749 13.26V9.58l.379-.096h.81l.237.095v.692h.511l.725-.791h.853l.175.246v1.464l-.18.19c-.085-.1-.384-.309-.9-.309c-.744 0-1.094.46-1.184.687v1.203l-1.052.483l-.374-.189z");
}

.n_77cjbij {
  stop-color: var(--svg-color--c3942c, #c3942c);
}

.nx97vtbsl {
  d: path("m12.887 9.661l-.412-.218l.156-.151h1.516l.204.27v.582l.88-.852h1.27l.237.364v1.706l-.303.364l-.176-.364l-.312-.663l-1.734-.247l-1.326-.796z");
}

.o1sr77egk {
  d: path("m6.945 11.839l-.63 1.26c0 1.032.043 3.424-.663 4.57l.01.015c.71-.867 1.42-2.975 1.42-3.903c0-.474-.066-1.256-.137-1.942");
}

.o2s8vwbmy {
  stop-color: var(--svg-color--9d7126, #9d7126);
}

.odgoljv5n {
  stop-color: var(--svg-color--79787d, #79787d);
}

.odhqnn32q {
  stop-color: var(--svg-color--7f7366, #7f7366);
}

.oli1qbc6g {
  stop-color: var(--svg-color--7d7975, #7d7975);
}

.pah8wbbim {
  stop-color: var(--svg-color--896d57, #896d57);
}

.pzq9w9r-z {
  stop-color: var(--svg-color--af764b, #af764b);
}

.q1rkk0lqr {
  d: path("m13.413 14.843l1.43 1.307v-1.307h.474v2.368h-.384l-1.511-1.369v1.37h-.474v-2.37z");
}

.q6r8l7blc {
  stop-color: var(--svg-color--c2a963, #c2a963);
}

.qfw73ibsw {
  stop-color: var(--svg-color--85867b, #85867b);
}

.rdk0dpevl {
  stop-color: var(--svg-color--a47316, #a47316);
}

.re1uklbnh {
  fill: var(--svg-color--c6c6c6, #c6c6c6);
  d: path("M6.837 10.835H4.374c.066.407-.128.512-.128.625c.673 1.019-.142 1.923-.677 2.71c1.956 1.378 1.999 3.282 2.093 3.514c.711-.866 1.422-2.974 1.422-3.903c0-.743-.166-2.273-.252-2.946z");
}

.rholo2byn {
  stop-color: var(--svg-color--bb802d, #bb802d);
}

.rzwbe1teq {
  stop-color: var(--svg-color--a9814e, #a9814e);
}

.txjovrb-z {
  d: path("M5.62 17.51a3.83 3.83 0 0 0-1.592-3.344h-.483a5.14 5.14 0 0 1 2.07 3.32v.024z");
}

.uik8v9b0b {
  stop-color: var(--svg-color--70614a, #70614a);
}

.umxypt-8g {
  fill: var(--svg-color--bcbbb9, #bcbbb9);
  d: path("M8.444 9.632v.753c.095-.066.407-.194.905-.194c.63 0 .9.19.9.687c0 .493-.27.582-.9.701c-.498.095-.735.355-.787.474v1.217c.024.057.095.17.161.17c.479-.246 2.16-.217 2.942-.17v-3.131c0-.246-.526-.805-1.686-.805c-.934 0-1.412.194-1.535.293z");
}

.uouse2bfu {
  fill-rule: evenodd;
  d: path("M16.505 14.843h-.715v2.368h.715a1.184 1.184 0 1 0 0-2.368m-.004.473h-.237v1.422h.237a.71.71 0 0 0 0-1.422");
}

.v35tnxrhg {
  d: path("m3.602 11.168l.346-.635l-.943-.744c.048.545.36 1.075.597 1.374z");
}

.wtl3ii3lq {
  fill: var(--svg-color--776e5f, #776e5f);
  d: path("M6.62 6.316c-.246 0-.672.35-.852.52l.79.815c.237-.142.72-.473.72-.71c0-.294-.35-.625-.658-.625");
}

.wu31gdcmy {
  stop-color: var(--svg-color--7a7975, #7a7975);
}

.ww8v6oywb {
  d: path("M9.158 14.843h-.474v2.368h1.421v-.473h-.947z");
}

.xsdc5kbga {
  stop-color: var(--svg-color--e1c08d, #e1c08d);
}

.z2knq8z3y {
  fill: var(--svg-color--614108, #614108);
  d: path("M6.79 7.832L5.77 6.79l-.696.701l.142.133l-.142.204h-.18v1.804c.275-.033.947-.132 1.44-.236c-.052-1.09.284-1.502.455-1.568z");
}

.z7uaz7boh {
  d: path("m11.26 14.843l-.682 2.368h.535l.412-1.44l.413 1.44h.535l-.682-2.368z");
}

.zclfcabzu {
  d: path("M8.164 11.229c-.095-.256-.356-.649-.782-.649c-.346 0-.64.308-.8.545c.16-.142.426-.308.72-.308c.416 0 .696.256.862.407z");
}

.zgx1r5b0h {
  fill: var(--svg-color--bcbbb9, #bcbbb9);
  d: path("M17.442 9.632v.753c.095-.066.408-.194.905-.194c.63 0 .9.19.9.687c0 .493-.27.582-.9.701c-.497.095-.734.355-.786.474v1.217c.023.057.095.17.16.17c.48-.246 2.16-.217 2.942-.17v-3.131c0-.246-.525-.805-1.686-.805c-.933 0-1.411.194-1.535.293z");
}

</style>
