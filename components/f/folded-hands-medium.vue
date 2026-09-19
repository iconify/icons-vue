<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#itYQeoe)" class="eud_w5b5b"/><rect fill="url(#iZJWgWg)" class="eud_w5b5b"/><path fill="url(#ihzDmli)" class="kwu0ecbgx"/><path fill="url(#irDOhse)" class="kwu0ecbgx"/><path fill="url(#irt7Ofc)" class="kwu0ecbgx"/><rect fill="url(#ik3W4ke)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><rect fill="url(#iwwdkob)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><path fill="url(#i5jlLnb)" class="aya86ob_i"/><path fill="url(#i9pOGIW)" class="aya86ob_i"/><g filter="url(#ipf6Krc)"><path stroke="url(#irKZvXN)" class="p5r1espwo"/></g><g filter="url(#i6etw0K)"><path stroke="url(#iLB5T0c)" class="eqwqidcpi"/></g><g filter="url(#icjI4hc)"><path fill="url(#ixfO6qU)" class="eqto79wbm"/></g><g filter="url(#iC0Bm1b)"><path fill="url(#i89Nfte)" class="qxwbxgb_x"/></g><g filter="url(#iy4pzgd)"><ellipse fill="url(#i3ci3hb)" transform="rotate(-39.49 19.849 3.814)" class="r2u3ribwc"/></g><g filter="url(#ietFUkB)"><ellipse transform="rotate(-39.49 15.456 3.855)" class="k7v8wobpp"/></g><path fill="url(#irQWWGv)" class="c2ymzseoj"/><path fill="url(#iuSxZld)" class="c2ymzseoj"/><path fill="url(#izNVhmg)" class="c2ymzseoj"/><path fill="url(#iylUNWc)" class="c2ymzseoj"/><path fill="url(#iuwFvwc)" class="c2ymzseoj"/><path fill="url(#iGE9STf)" class="n418v0b3f"/><path fill="url(#ilma3Md)" class="n418v0b3f"/><path fill="url(#iSNOo9d)" class="n418v0b3f"/><path fill="url(#iEIz0mc)" class="n418v0b3f"/><defs><linearGradient id="iZJWgWg" x1="14.453" x2="14.453" y1="6.938" y2="4" gradientUnits="userSpaceOnUse"><stop class="feeel8b1e"/><stop offset="1" class="ivifb63au"/></linearGradient><linearGradient id="ihzDmli" x1="13.269" x2="13.269" y1="5.125" y2="16.702" gradientUnits="userSpaceOnUse"><stop class="x-prxkl0q"/><stop offset="1" class="ihcoeb3rx"/></linearGradient><linearGradient id="irt7Ofc" x1="16.984" x2="16.297" y1="12.544" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="v38_124ks"/><stop offset="1" class="ayb-bp0iz"/></linearGradient><linearGradient id="iwwdkob" x1="2.922" x2="2.922" y1="6.09" y2="1.496" gradientUnits="userSpaceOnUse"><stop class="tu7s41bgq"/><stop offset="1" class="y_tfadbgo"/></linearGradient><linearGradient id="i5jlLnb" x1="20.699" x2="20.699" y1="8.915" y2="22.188" gradientUnits="userSpaceOnUse"><stop class="w9718jb5f"/><stop offset="1" class="dlnnqibvg"/></linearGradient><linearGradient id="irKZvXN" x1="25.265" x2="25.265" y1="16.348" y2="25.857" gradientUnits="userSpaceOnUse"><stop class="wci41ibjf"/><stop offset=".49" class="fhsjt5paq"/><stop offset="1" class="wci41ibjf"/></linearGradient><linearGradient id="iLB5T0c" x1="10.914" x2="16.958" y1="15.896" y2="23.236" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bctddzirn"/><stop offset=".49" class="j8pwmbb_m"/><stop offset=".776" class="bctddzirn"/></linearGradient><linearGradient id="ixfO6qU" x1="20.954" x2="20.954" y1="5.765" y2="24.331" gradientUnits="userSpaceOnUse"><stop class="aik-0t3vt"/><stop offset="1" class="regjr8beg"/></linearGradient><linearGradient id="i89Nfte" x1="16.759" x2="12.234" y1="6.778" y2="31.761" gradientUnits="userSpaceOnUse"><stop class="ao_f_xb-n"/><stop offset="1" class="hoii9jxdj"/></linearGradient><linearGradient id="i3ci3hb" x1="19.849" x2="19.849" y1="2.68" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="n358k1byr"/><stop offset="1" class="r_su1zbrm"/></linearGradient><linearGradient id="irQWWGv" x1="7.609" x2="13.234" y1="15.195" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="q9gpy7bkq"/><stop offset="1" class="d5z2kxb0h"/></linearGradient><linearGradient id="iuSxZld" x1="13.633" x2="12.784" y1="18.983" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iylUNWc" x1="8.357" x2="9.211" y1="22.593" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="tyfxpdb0w"/><stop offset="1" class="ki9m_gb7k"/></linearGradient><linearGradient id="iuwFvwc" x1="13.297" x2="12.992" y1="26.703" y2="26.359" gradientUnits="userSpaceOnUse"><stop class="opu5b_bed"/><stop offset="1" class="t2er4acdn"/></linearGradient><linearGradient id="iGE9STf" x1="23.735" x2="19.084" y1="18.733" y2="28.212" gradientUnits="userSpaceOnUse"><stop class="b1lbi7bol"/><stop offset="1" class="k03uj4bcp"/></linearGradient><linearGradient id="iSNOo9d" x1="20.335" x2="20.88" y1="18.983" y2="19.439" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iEIz0mc" x1="20.672" x2="20.914" y1="26.703" y2="26.422" gradientUnits="userSpaceOnUse"><stop class="ewlg17b4k"/><stop offset="1" class="b5b0myb0o"/></linearGradient><radialGradient id="itYQeoe" cx="0" cy="0" r="1" gradientTransform="rotate(105.944 7.283 7.238)scale(6.02483 2.63146)" gradientUnits="userSpaceOnUse"><stop class="kynlb4buu"/><stop offset="0" class="on1wrzb_k"/><stop offset="1" class="kynlb4buu"/></radialGradient><radialGradient id="irDOhse" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 15.865 23.496)" gradientUnits="userSpaceOnUse"><stop class="z3l91pfnd"/><stop offset="1" class="zwprpfh3p"/></radialGradient><radialGradient id="ik3W4ke" cx="0" cy="0" r="1" gradientTransform="rotate(76.079 -.2 .937)scale(4.74993 3.74633)" gradientUnits="userSpaceOnUse"><stop class="qe0mx1bpp"/><stop offset="1" class="z6qej_r-e"/></radialGradient><radialGradient id="i9pOGIW" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 18.103 23.496)" gradientUnits="userSpaceOnUse"><stop class="yfklaqdqx"/><stop offset="1" class="j_n35_pkg"/></radialGradient><radialGradient id="izNVhmg" cx="0" cy="0" r="1" gradientTransform="rotate(-45 34.16 1.731)scale(8.65467 3.14404)" gradientUnits="userSpaceOnUse"><stop class="w6o4myf_b"/><stop offset="1" class="c8s6441kg"/></radialGradient><radialGradient id="ilma3Md" cx="0" cy="0" r="1" gradientTransform="matrix(4.15623 3.31253 -1.73902 2.18195 22.078 17.063)" gradientUnits="userSpaceOnUse"><stop class="cpbnylbqu"/><stop offset="1" class="bgm6-ubvx"/></radialGradient><filter id="ipf6Krc" width=".65" height="8.419" x="24.44" y="16.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4073" stdDeviation=".125"/></filter><filter id="i6etw0K" width="5.65" height="6.709" x="10.725" y="16.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4073" stdDeviation=".125"/></filter><filter id="icjI4hc" width="6.934" height="13.95" x="17.266" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4073" stdDeviation=".75"/></filter><filter id="iC0Bm1b" width="8.303" height="18.853" x="9.476" y="4.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4073" stdDeviation=".75"/></filter><filter id="iy4pzgd" width="3.928" height="4.044" x="17.885" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4073" stdDeviation=".5"/></filter><filter id="ietFUkB" width="3.753" height="3.85" x="13.579" y="1.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4073" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:folded-hands-medium" /></template>
<style>
.aik-0t3vt {
  stop-color: var(--svg-color--cea68c, #CEA68C);
}

.ao_f_xb-n {
  stop-color: var(--svg-color--cca58d, #CCA58D);
}

.aya86ob_i {
  d: path("M19.19 4.737c1.218 0 2.205.987 2.205 2.205v5.4a2 2 0 0 0 .69 1.512l2.33 2.018l-6.47 7.624l-.654-.635a.96.96 0 0 1-.303-.7v-4.094l-.004-.128V6.942c0-1.218.988-2.205 2.206-2.205");
}

.ayb-bp0iz {
  stop-color: var(--svg-color--5f3d35, #5F3D35);
  stop-opacity: 0;
}

.b1lbi7bol {
  stop-color: var(--svg-color--945bcc, #945BCC);
}

.b5b0myb0o {
  stop-color: var(--svg-color--9469ff, #9469FF);
  stop-opacity: 0;
}

.bctddzirn {
  stop-color: var(--svg-color--9867f8, #9867F8);
  stop-opacity: 0;
}

.bgm6-ubvx {
  stop-color: var(--svg-color--9d5bef, #9D5BEF);
  stop-opacity: 0;
}

.c2ymzseoj {
  d: path("M16.645 22.903L10.36 15.41a.6.6 0 0 0-.822-.093l-.358.27a1 1 0 0 0-.398.799V29.74a.25.25 0 0 0 .41.192l7.38-6.184a.6.6 0 0 0 .074-.846");
}

.c8s6441kg {
  stop-color: var(--svg-color--8253ff, #8253FF);
  stop-opacity: 0;
}

.cp95w770i {
  stop-color: var(--svg-color--6c2ac4, #6C2AC4);
}

.cpbnylbqu {
  stop-color: var(--svg-color--9d5bef, #9D5BEF);
}

.d5z2kxb0h {
  stop-color: var(--svg-color--6d43ff, #6D43FF);
}

.dk3ah5owx {
  stop-color: var(--svg-color--6c2ac4, #6C2AC4);
  stop-opacity: 0;
}

.dlnnqibvg {
  stop-color: var(--svg-color--8c5f59, #8C5F59);
}

.e4xcmebwj {
  width: 4.39px;
  height: 8.125px;
  rx: 2.195px;
}

.eqto79wbm {
  d: path("M20.898 6.831a1.066 1.066 0 0 0-2.132 0v6.641c0 .734.309 1.435.85 1.93l1.093 1.001a1.19 1.19 0 0 0 1.627-1.734l-.918-.882c-.332-.32-.52-.76-.52-1.221z");
}

.eqwqidcpi {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("m11.033 16.827l5.034 6.113");
}

.eud_w5b5b {
  width: 4.39px;
  height: 8.125px;
  x: 12.594px;
  y: 2.223px;
  rx: 2.195px;
}

.ewlg17b4k {
  stop-color: var(--svg-color--9469ff, #9469FF);
}

.feeel8b1e {
  stop-color: var(--svg-color--6f533e, #6F533E);
}

.fhsjt5paq {
  stop-color: var(--svg-color--a578ff, #A578FF);
}

.ft5dv1b6b {
  fill: none;
}

.hoii9jxdj {
  stop-color: var(--svg-color--cca58d, #CCA58D);
  stop-opacity: 0;
}

.ihcoeb3rx {
  stop-color: var(--svg-color--997263, #997263);
}

.ivifb63au {
  stop-color: var(--svg-color--6f533e, #6F533E);
  stop-opacity: 0;
}

.j_n35_pkg {
  stop-color: var(--svg-color--743867, #743867);
  stop-opacity: 0;
}

.j8pwmbb_m {
  stop-color: var(--svg-color--9867f8, #9867F8);
}

.k03uj4bcp {
  stop-color: var(--svg-color--573eff, #573EFF);
}

.k7v8wobpp {
  cx: 15.456px;
  cy: 3.855px;
  fill: var(--svg-color--c9a487, #C9A487);
  rx: 0.764px;
  ry: 1.019px;
}

.ki9m_gb7k {
  stop-color: var(--svg-color--6236ae, #6236AE);
  stop-opacity: 0;
}

.kwu0ecbgx {
  d: path("M14.779 4.737a2.206 2.206 0 0 0-2.206 2.205v5.4a2 2 0 0 1-.69 1.512l-2.33 2.018l6.47 7.624l.654-.635a1 1 0 0 0 .323-.713c-.024-5.068-.016-10.137-.016-15.206a2.206 2.206 0 0 0-2.206-2.205");
}

.kynlb4buu {
  stop-color: var(--svg-color--92705a, #92705A);
}

.n358k1byr {
  stop-color: var(--svg-color--cfa88b, #CFA88B);
}

.n418v0b3f {
  d: path("m17.323 22.903l6.287-7.494a.6.6 0 0 1 .821-.093l.358.27a1 1 0 0 1 .398.799V29.74a.25.25 0 0 1-.41.192l-7.38-6.184a.6.6 0 0 1-.074-.846");
}

.on1wrzb_k {
  stop-color: var(--svg-color--bd9a7d, #BD9A7D);
}

.opu5b_bed {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
}

.p5r1espwo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.765 17.143v7.92");
}

.q9gpy7bkq {
  stop-color: var(--svg-color--6640a2, #6640A2);
}

.qe0mx1bpp {
  stop-color: var(--svg-color--c4a083, #C4A083);
}

.qxwbxgb_x {
  d: path("M14.147 6.66a1.066 1.066 0 0 1 2.132 0v12.503a2.284 2.284 0 0 1-4.272 1.124l-.643-1.137a3 3 0 0 1 .46-3.567l1.758-1.81a2 2 0 0 0 .565-1.393z");
}

.r_su1zbrm {
  stop-color: var(--svg-color--cfa88b, #CFA88B);
  stop-opacity: 0;
}

.r2u3ribwc {
  cx: 19.849px;
  cy: 3.814px;
  rx: 0.828px;
  ry: 1.134px;
}

.regjr8beg {
  stop-color: var(--svg-color--cea68c, #CEA68C);
  stop-opacity: 0;
}

.t2er4acdn {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
  stop-opacity: 0;
}

.tu7s41bgq {
  stop-color: var(--svg-color--694630, #694630);
}

.tyfxpdb0w {
  stop-color: var(--svg-color--6236ae, #6236AE);
}

.v38_124ks {
  stop-color: var(--svg-color--5f3d35, #5F3D35);
}

.w6o4myf_b {
  stop-color: var(--svg-color--8253ff, #8253FF);
}

.w9718jb5f {
  stop-color: var(--svg-color--a67f6a, #A67F6A);
}

.wci41ibjf {
  stop-color: var(--svg-color--9a69fb, #9A69FB);
  stop-opacity: 0;
}

.x-prxkl0q {
  stop-color: var(--svg-color--a17b67, #A17B67);
}

.y_tfadbgo {
  stop-color: var(--svg-color--694630, #694630);
  stop-opacity: 0;
}

.yfklaqdqx {
  stop-color: var(--svg-color--743867, #743867);
}

.z3l91pfnd {
  stop-color: var(--svg-color--7a4274, #7A4274);
}

.z6qej_r-e {
  stop-color: var(--svg-color--8d6c56, #8D6C56);
}

.zwprpfh3p {
  stop-color: var(--svg-color--7a4274, #7A4274);
  stop-opacity: 0;
}

</style>
