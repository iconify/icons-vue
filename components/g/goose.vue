<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ioxHKob)" class="ceucw_lao"/><path fill="url(#iA9xHhd)" class="ceucw_lao"/><path fill="url(#iulzHtd)" class="af09r12sc"/><path fill="url(#iytGVWb)" class="af09r12sc"/><path fill="url(#iT3bRWc)" class="af09r12sc"/><path fill="url(#iIBLm4d)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iac7QUb)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#ifrnAKI)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iuGEvpe)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iJay1OP)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iMTfoEb)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#i1AlsQe)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iarH4bd)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iBhqqqb)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iAeiolb)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iMKFDeC)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iUlbD4c)" clip-rule="evenodd" class="jnft5mbvh"/><path fill="url(#iO6JPnS)" class="v2p7xmfml"/><path fill="url(#i50Bite)" class="v2p7xmfml"/><path fill="url(#iRIps7d)" class="ewl87bcek"/><path fill="url(#iW8Tnpc)" class="ewl87bcek"/><path fill="url(#izN3hwb)" class="ewl87bcek"/><path fill="url(#i0dAgLj)" class="m9z0mobga"/><path class="uetnazbtx"/><path fill="url(#iUvVONe)" class="mgnemidhe"/><path fill="url(#i37buqu)" class="mgnemidhe"/><path fill="url(#iIjAIZP)" class="mgnemidhe"/><path fill="url(#i1OXsXQ)" class="mgnemidhe"/><path fill="url(#i1WwyKb)" class="mgnemidhe"/><defs><radialGradient id="ioxHKob" cx="0" cy="0" r="1" gradientTransform="matrix(-.74999 4.9375 -5.35172 -.8129 16.188 28.593)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="ziyu8lb5n"/><stop offset=".6" class="l61_zxbkr"/></radialGradient><radialGradient id="iA9xHhd" cx="0" cy="0" r="1" gradientTransform="rotate(168.252 6.97 15.75)scale(1.15107 1.24763)" gradientUnits="userSpaceOnUse"><stop offset=".387" class="ue_821djl"/><stop offset="1" class="kb35t-b7x"/></radialGradient><radialGradient id="iT3bRWc" cx="0" cy="0" r="1" gradientTransform="rotate(-63.016 32.323 1.56)scale(3.82238 1.8573)" gradientUnits="userSpaceOnUse"><stop class="jumk_jbvs"/><stop offset=".391" class="m_ulzubqu"/></radialGradient><radialGradient id="iIBLm4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 27.1875 -21.9829 0 17.3 -.897)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="sckqkam-t"/><stop offset=".968" class="gd9lsub4l"/></radialGradient><radialGradient id="iac7QUb" cx="0" cy="0" r="1" gradientTransform="matrix(1.49998 3.31251 -2.44435 1.10685 12.811 16.375)" gradientUnits="userSpaceOnUse"><stop offset=".421" class="jan8zubqz"/><stop offset="1" class="q_zz9obac"/></radialGradient><radialGradient id="ifrnAKI" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43752 6.24998 -1.97457 -1.08602 13.188 11.188)" gradientUnits="userSpaceOnUse"><stop offset=".421" class="qvl1gfb1p"/><stop offset="1" class="j-34kzhlq"/></radialGradient><radialGradient id="iuGEvpe" cx="0" cy="0" r="1" gradientTransform="matrix(.3125 4.9375 -6.09485 .38575 17.125 18.469)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="wv7306b3y"/><stop offset=".799" class="fblwloqyy"/></radialGradient><radialGradient id="iJay1OP" cx="0" cy="0" r="1" gradientTransform="rotate(115.963 8.33 15.25)scale(10.6359 4.70051)" gradientUnits="userSpaceOnUse"><stop offset=".203" class="bkf2obvlv"/><stop offset="1" class="siuw1zb7o"/></radialGradient><radialGradient id="iMTfoEb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.78127 7.75 -1.65543 -.8077 25.344 14.625)" gradientUnits="userSpaceOnUse"><stop offset=".177" class="o9aoymbwc"/><stop offset="1" class="yegg26bgk"/></radialGradient><radialGradient id="i1AlsQe" cx="0" cy="0" r="1" gradientTransform="rotate(123.247 5.097 9.172)scale(6.72594 2.67458)" gradientUnits="userSpaceOnUse"><stop offset=".743" class="rr1ssvtpx"/><stop offset="1" class="qextbdczl"/></radialGradient><radialGradient id="iarH4bd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.34375 0 0 -6.2168 14.469 2.03)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="zjfrf78oa"/><stop offset="1" class="cv8bilyil"/></radialGradient><radialGradient id="iBhqqqb" cx="0" cy="0" r="1" gradientTransform="matrix(3.71875 .15625 -.1153 2.74413 10.875 7.781)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="oeiss_l6k"/><stop offset="1" class="txijhsyql"/></radialGradient><radialGradient id="iAeiolb" cx="0" cy="0" r="1" gradientTransform="rotate(90 3.516 9.016)scale(1.40625)" gradientUnits="userSpaceOnUse"><stop class="lyahjmzfe"/><stop offset="1" class="v6o850bwb"/></radialGradient><radialGradient id="iMKFDeC" cx="0" cy="0" r="1" gradientTransform="rotate(135 6.726 4.8)scale(3.18198)" gradientUnits="userSpaceOnUse"><stop class="k8h5k7byq"/><stop offset="1" class="qjsfddz1j"/></radialGradient><radialGradient id="iUlbD4c" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 7.273 14.165)scale(2.57391 1.89933)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="x61hc8bxk"/><stop offset=".907" class="toe2v196h"/></radialGradient><radialGradient id="iO6JPnS" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.875 -12.5438 0 13.886 17.232)" gradientUnits="userSpaceOnUse"><stop offset=".403" class="n-ymu85vw"/><stop offset=".514" class="gpdazcbld"/></radialGradient><radialGradient id="i50Bite" cx="0" cy="0" r="1" gradientTransform="matrix(-1.19336 7.625 -11.30202 -1.76884 12.438 24.938)" gradientUnits="userSpaceOnUse"><stop class="avgavvbqt"/><stop offset="1" class="m4rkc932d"/></radialGradient><radialGradient id="iRIps7d" cx="0" cy="0" r="1" gradientTransform="rotate(78.518 1.046 7.445)scale(3.25259 2.99818)" gradientUnits="userSpaceOnUse"><stop offset=".43" class="pc35vkhly"/><stop offset="1" class="cjq7fm79d"/></radialGradient><radialGradient id="iW8Tnpc" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 1.25 -2.72656 1.22695 7.906 4.625)" gradientUnits="userSpaceOnUse"><stop offset=".595" class="lckhw2_pz"/><stop offset="1" class="phtlntbag"/></radialGradient><radialGradient id="izN3hwb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.1953 -.65603 -.54884 10.188 3.18)" gradientUnits="userSpaceOnUse"><stop offset=".424" class="ztiaqe26k"/><stop offset="1" class="p78dtvbsy"/></radialGradient><radialGradient id="i0dAgLj" cx="0" cy="0" r="1" gradientTransform="rotate(113.15 4.902 6.95)scale(.76316)" gradientUnits="userSpaceOnUse"><stop class="ggr5g-70s"/><stop offset="1" class="is2vskbrg"/></radialGradient><radialGradient id="iUvVONe" cx="0" cy="0" r="1" gradientTransform="matrix(5.40628 7.65623 -6.81838 4.81465 16.563 14.125)" gradientUnits="userSpaceOnUse"><stop offset=".58" class="q-48jxi4f"/><stop offset=".713" class="yv23tqbma"/><stop offset=".809" class="q-48jxi4f"/></radialGradient><radialGradient id="iIjAIZP" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 -4.15234 5.24613 2.3689 12.188 21.965)" gradientUnits="userSpaceOnUse"><stop offset=".466" class="zk25bov3u"/><stop offset=".963" class="ea7m8ja_v"/></radialGradient><radialGradient id="i1OXsXQ" cx="0" cy="0" r="1" gradientTransform="matrix(8.74999 5.5 -7.15297 11.37973 13.719 14.875)" gradientUnits="userSpaceOnUse"><stop offset=".88" class="bi6lwhrqb"/><stop offset=".97" class="e2grv6b4j"/></radialGradient><radialGradient id="i1WwyKb" cx="0" cy="0" r="1" gradientTransform="matrix(.28125 5.625 -10.69824 .53491 17.688 16.5)" gradientUnits="userSpaceOnUse"><stop offset=".531" class="ffnzwbbyl"/><stop offset=".949" class="stj_khb5c"/></radialGradient><linearGradient id="iulzHtd" x1="18.451" x2="19.5" y1="27.469" y2="27.469" gradientUnits="userSpaceOnUse"><stop class="ocblmcbnc"/><stop offset=".27" class="iblcfjbpc"/><stop offset=".672" class="j2k67e-4z"/><stop offset=".985" class="xnxf0re5w"/></linearGradient><linearGradient id="iytGVWb" x1="18.451" x2="18.451" y1="28.828" y2="29.984" gradientUnits="userSpaceOnUse"><stop class="f63jjabrq"/><stop offset=".189" class="kz9mc36tp"/><stop offset=".865" class="kz9mc36tp"/><stop offset="1" class="qa73jud5o"/></linearGradient><linearGradient id="i37buqu" x1="12.967" x2="22.375" y1="18.906" y2="16.719" gradientUnits="userSpaceOnUse"><stop offset=".372" class="dg4j6acff"/><stop offset=".73" class="gv5nv_8gy"/><stop offset=".93" class="u8t3ytk2q"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:goose" /></template>
<style>
.af09r12sc {
  d: path("M19.451 25.328h-1v3.656H17.31a.88.88 0 0 0-.881.882c0 .065.053.118.118.118h3.791a.137.137 0 0 0 .138-.137a.863.863 0 0 0-.863-.863h-.16z");
}

.avgavvbqt {
  stop-color: var(--svg-color--9374af, #9374AF);
}

.bi6lwhrqb {
  stop-color: var(--svg-color--ab5749, #AB5749);
  stop-opacity: 0;
}

.bkf2obvlv {
  stop-color: var(--svg-color--ba7063, #BA7063);
}

.ceucw_lao {
  d: path("M16.373 25.328h-1v3.656h-1.142a.88.88 0 0 0-.881.882c0 .065.053.118.118.118h4.791a.137.137 0 0 0 .137-.137a.863.863 0 0 0-.862-.863h-1.161z");
}

.cjq7fm79d {
  stop-color: var(--svg-color--fb6d31, #FB6D31);
}

.cv8bilyil {
  stop-color: var(--svg-color--b68071, #B68071);
  stop-opacity: 0;
}

.dg4j6acff {
  stop-color: var(--svg-color--ab6856, #AB6856);
}

.e2grv6b4j {
  stop-color: var(--svg-color--ab5749, #AB5749);
}

.ea7m8ja_v {
  stop-color: var(--svg-color--884a48, #884A48);
  stop-opacity: 0;
}

.ewl87bcek {
  d: path("M10.407 3.18C9.291 4.349 8.291 5.582 6.464 5.582h-.237c-.2 0-.366.165-.366.365a1.79 1.79 0 0 0 1.786 1.786h2.76z");
}

.f63jjabrq {
  stop-color: var(--svg-color--ff7027, #FF7027);
  stop-opacity: 0;
}

.fblwloqyy {
  stop-color: var(--svg-color--8d4b4c, #8D4B4C);
  stop-opacity: 0;
}

.ffnzwbbyl {
  stop-color: var(--svg-color--9b4a58, #9B4A58);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gd9lsub4l {
  stop-color: var(--svg-color--8b374a, #8B374A);
}

.ggr5g-70s {
  stop-color: var(--svg-color--57484c, #57484C);
}

.gpdazcbld {
  stop-color: var(--svg-color--a9a5ad, #A9A5AD);
}

.gv5nv_8gy {
  stop-color: var(--svg-color--b06661, #B06661);
  stop-opacity: 0.63;
}

.iblcfjbpc {
  stop-color: var(--svg-color--fb6421, #FB6421);
}

.is2vskbrg {
  stop-color: var(--svg-color--39202b, #39202B);
}

.j-34kzhlq {
  stop-color: var(--svg-color--b76c63, #B76C63);
  stop-opacity: 0;
}

.j2k67e-4z {
  stop-color: var(--svg-color--ff7e48, #FF7E48);
}

.jan8zubqz {
  stop-color: var(--svg-color--c07c6b, #C07C6B);
}

.jnft5mbvh {
  fill-rule: evenodd;
  d: path("M16.017 5.12c0 .11-.006.497-.055.741c-.105.526-.474 1.366-.697 1.869l-.024.012l-2.312 4.328c-.19.466-.487 1.633-.156 2.57c.329.93 1.39.89 2.117.86q.172-.007.313-.008H22c.136-.01.347-.048.573-.13l.006.006c.448-.134.844-.518 1.268-1.205c.294-.477.65-.776 1.178-.63c.424.117.587.33.75.777c.416 1.132.398 2.705.322 3.496c-.195 2.03-.917 3.93-2.096 5.296c-1.594 1.849-3.978 2.842-6.61 2.892a5 5 0 0 1-.22.006c-1.675 0-2.406-.104-2.562-.156c-1.375-.537-4.353-2.144-5.266-4.282c-1.14-2.671-1.187-7.25-.14-9.062c.736-1.275 2.067-3.229 2.852-4.348a6 6 0 0 1-.603-.422h-1.05c-.687-.429-.683-1.355-.679-2.491l.001-.28c0-1.56 1.464-2.93 3.148-2.93s3.145 1.497 3.145 3.092");
}

.jumk_jbvs {
  stop-color: var(--svg-color--db5813, #DB5813);
}

.k8h5k7byq {
  stop-color: var(--svg-color--c67d6a, #C67D6A);
}

.kb35t-b7x {
  stop-color: var(--svg-color--c33517, #C33517);
  stop-opacity: 0;
}

.kz9mc36tp {
  stop-color: var(--svg-color--ff7a41, #FF7A41);
}

.l61_zxbkr {
  stop-color: var(--svg-color--ba331a, #BA331A);
}

.lckhw2_pz {
  stop-color: var(--svg-color--f99768, #F99768);
}

.lyahjmzfe {
  stop-color: var(--svg-color--a04e49, #A04E49);
}

.m_ulzubqu {
  stop-color: var(--svg-color--db5813, #DB5813);
  stop-opacity: 0;
}

.m4rkc932d {
  stop-color: var(--svg-color--9374af, #9374AF);
  stop-opacity: 0;
}

.m9z0mobga {
  d: path("M12.919 5.877a.702.702 0 1 0 0-1.404a.702.702 0 0 0 0 1.404");
}

.mgnemidhe {
  d: path("M13.531 20.25c-1.275-1.55-.086-3.844.602-4.75c2.187 0 6.607-.031 7.273-.031s1.163-.063 1.335-.172c.896.114.64 3.007-.18 4.14c-2.687 3.72-7.436 2.75-9.03.813");
}

.n-ymu85vw {
  stop-color: var(--svg-color--cfc5db, #CFC5DB);
}

.o9aoymbwc {
  stop-color: var(--svg-color--c27c6b, #C27C6B);
}

.ocblmcbnc {
  stop-color: var(--svg-color--d15723, #D15723);
}

.oeiss_l6k {
  stop-color: var(--svg-color--864a46, #864A46);
}

.p78dtvbsy {
  stop-color: var(--svg-color--e18b64, #E18B64);
  stop-opacity: 0;
}

.pc35vkhly {
  stop-color: var(--svg-color--ff803a, #FF803A);
}

.phtlntbag {
  stop-color: var(--svg-color--f99768, #F99768);
  stop-opacity: 0;
}

.q_zz9obac {
  stop-color: var(--svg-color--b76e62, #B76E62);
  stop-opacity: 0;
}

.q-48jxi4f {
  stop-color: var(--svg-color--c17c6e, #C17C6E);
  stop-opacity: 0;
}

.qa73jud5o {
  stop-color: var(--svg-color--ee582a, #EE582A);
}

.qextbdczl {
  stop-color: var(--svg-color--a05b4b, #A05B4B);
  stop-opacity: 0;
}

.qjsfddz1j {
  stop-color: var(--svg-color--c67d6a, #C67D6A);
  stop-opacity: 0;
}

.qvl1gfb1p {
  stop-color: var(--svg-color--b76c63, #B76C63);
}

.rr1ssvtpx {
  stop-color: var(--svg-color--a05b4b, #A05B4B);
}

.sckqkam-t {
  stop-color: var(--svg-color--ac645b, #AC645B);
}

.siuw1zb7o {
  stop-color: var(--svg-color--ba7063, #BA7063);
  stop-opacity: 0;
}

.stj_khb5c {
  stop-color: var(--svg-color--9b4a58, #9B4A58);
}

.toe2v196h {
  stop-color: var(--svg-color--a96756, #A96756);
  stop-opacity: 0;
}

.txijhsyql {
  stop-color: var(--svg-color--9f5551, #9F5551);
  stop-opacity: 0;
}

.u8t3ytk2q {
  stop-color: var(--svg-color--ab6856, #AB6856);
  stop-opacity: 0;
}

.ue_821djl {
  stop-color: var(--svg-color--c33517, #C33517);
}

.uetnazbtx {
  fill: var(--svg-color--b56e5b, #B56E5B);
  d: path("M13.531 20.25c-1.275-1.55-.086-3.844.602-4.75c2.187 0 6.607-.031 7.273-.031s1.163-.063 1.335-.172c.896.114.64 3.007-.18 4.14c-2.687 3.72-7.436 2.75-9.03.813");
}

.v2p7xmfml {
  d: path("M12.834 7.734h-1.35C7.143 12.797 6.372 17.175 8.11 21s5.48 4.87 7.133 4.914c-3.391-1.094-4.688-2.953-5.61-6.078c-.816-2.773-.305-7.043 3.434-11.598c.164-.199.025-.504-.232-.504");
}

.v6o850bwb {
  stop-color: var(--svg-color--a25752, #A25752);
  stop-opacity: 0;
}

.wv7306b3y {
  stop-color: var(--svg-color--863d36, #863D36);
}

.x61hc8bxk {
  stop-color: var(--svg-color--a96756, #A96756);
}

.xnxf0re5w {
  stop-color: var(--svg-color--ff7e38, #FF7E38);
}

.yegg26bgk {
  stop-color: var(--svg-color--c27c6b, #C27C6B);
  stop-opacity: 0;
}

.yv23tqbma {
  stop-color: var(--svg-color--c17c6e, #C17C6E);
}

.ziyu8lb5n {
  stop-color: var(--svg-color--e84f2d, #E84F2D);
}

.zjfrf78oa {
  stop-color: var(--svg-color--b68071, #B68071);
}

.zk25bov3u {
  stop-color: var(--svg-color--884a48, #884A48);
}

.ztiaqe26k {
  stop-color: var(--svg-color--e18b64, #E18B64);
}

</style>
