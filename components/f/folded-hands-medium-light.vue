<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#ijlHapb)" class="eud_w5b5b"/><rect fill="url(#ibVqedQ)" class="eud_w5b5b"/><path fill="url(#iHjJj5S)" class="kwu0ecbgx"/><path fill="url(#iClzQjb)" class="kwu0ecbgx"/><path fill="url(#iHMp3be)" class="kwu0ecbgx"/><rect fill="url(#iOvRkTB)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><rect fill="url(#iOK9rIc)" transform="matrix(-1 0 0 1 21.375 2.223)" class="e4xcmebwj"/><path fill="url(#ipN9bIc)" class="aya86ob_i"/><path fill="url(#ilL4HGX)" class="aya86ob_i"/><g filter="url(#iPVPZ1b)"><path stroke="url(#irKZvXN)" class="p5r1espwo"/></g><g filter="url(#i4sIBDe)"><path stroke="url(#iLB5T0c)" class="eqwqidcpi"/></g><g filter="url(#iAWdk2t)"><path fill="url(#i3Jaetc)" class="eqto79wbm"/></g><g filter="url(#ia0uKCF)"><path fill="url(#iZ2i4ic)" class="qxwbxgb_x"/></g><g filter="url(#iSKNrte)"><ellipse fill="url(#iZoeujd)" transform="rotate(-39.49 19.849 3.814)" class="r2u3ribwc"/></g><g filter="url(#ibMHgnc)"><ellipse transform="rotate(-39.49 15.456 3.855)" class="tn-0g6vdf"/></g><path fill="url(#irQWWGv)" class="c2ymzseoj"/><path fill="url(#iuSxZld)" class="c2ymzseoj"/><path fill="url(#izNVhmg)" class="c2ymzseoj"/><path fill="url(#iylUNWc)" class="c2ymzseoj"/><path fill="url(#iuwFvwc)" class="c2ymzseoj"/><path fill="url(#iGE9STf)" class="n418v0b3f"/><path fill="url(#ilma3Md)" class="n418v0b3f"/><path fill="url(#iSNOo9d)" class="n418v0b3f"/><path fill="url(#iEIz0mc)" class="n418v0b3f"/><defs><linearGradient id="ibVqedQ" x1="14.453" x2="14.453" y1="6.938" y2="4" gradientUnits="userSpaceOnUse"><stop class="xl55w_row"/><stop offset="1" class="sidzksbew"/></linearGradient><linearGradient id="iHjJj5S" x1="13.269" x2="13.269" y1="5.125" y2="16.702" gradientUnits="userSpaceOnUse"><stop class="ei0b1vpuw"/><stop offset="1" class="z-fmvxbyg"/></linearGradient><linearGradient id="iHMp3be" x1="16.984" x2="16.297" y1="12.544" y2="12.544" gradientUnits="userSpaceOnUse"><stop class="ty0tbvbnm"/><stop offset="1" class="h-3wzkb3q"/></linearGradient><linearGradient id="iOK9rIc" x1="2.922" x2="2.922" y1="6.09" y2="1.496" gradientUnits="userSpaceOnUse"><stop class="w9048gbal"/><stop offset="1" class="tkn2a3_jz"/></linearGradient><linearGradient id="ipN9bIc" x1="20.699" x2="20.699" y1="8.915" y2="22.188" gradientUnits="userSpaceOnUse"><stop class="juw1kcb0o"/><stop offset="1" class="ikko89bda"/></linearGradient><linearGradient id="irKZvXN" x1="25.265" x2="25.265" y1="16.348" y2="25.857" gradientUnits="userSpaceOnUse"><stop class="wci41ibjf"/><stop offset=".49" class="fhsjt5paq"/><stop offset="1" class="wci41ibjf"/></linearGradient><linearGradient id="iLB5T0c" x1="10.914" x2="16.958" y1="15.896" y2="23.236" gradientUnits="userSpaceOnUse"><stop offset=".214" class="bctddzirn"/><stop offset=".49" class="j8pwmbb_m"/><stop offset=".776" class="bctddzirn"/></linearGradient><linearGradient id="i3Jaetc" x1="20.954" x2="20.954" y1="5.765" y2="24.331" gradientUnits="userSpaceOnUse"><stop class="p5ok_v3pi"/><stop offset="1" class="b98qsobty"/></linearGradient><linearGradient id="iZ2i4ic" x1="16.759" x2="12.234" y1="6.778" y2="31.761" gradientUnits="userSpaceOnUse"><stop class="not7hp43l"/><stop offset="1" class="gbq2iq9ef"/></linearGradient><linearGradient id="iZoeujd" x1="19.849" x2="19.849" y1="2.68" y2="6.352" gradientUnits="userSpaceOnUse"><stop class="idp81whyl"/><stop offset="1" class="hx5258b2u"/></linearGradient><linearGradient id="irQWWGv" x1="7.609" x2="13.234" y1="15.195" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="q9gpy7bkq"/><stop offset="1" class="d5z2kxb0h"/></linearGradient><linearGradient id="iuSxZld" x1="13.633" x2="12.784" y1="18.983" y2="19.781" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iylUNWc" x1="8.357" x2="9.211" y1="22.593" y2="22.593" gradientUnits="userSpaceOnUse"><stop class="tyfxpdb0w"/><stop offset="1" class="ki9m_gb7k"/></linearGradient><linearGradient id="iuwFvwc" x1="13.297" x2="12.992" y1="26.703" y2="26.359" gradientUnits="userSpaceOnUse"><stop class="opu5b_bed"/><stop offset="1" class="t2er4acdn"/></linearGradient><linearGradient id="iGE9STf" x1="23.735" x2="19.084" y1="18.733" y2="28.212" gradientUnits="userSpaceOnUse"><stop class="b1lbi7bol"/><stop offset="1" class="k03uj4bcp"/></linearGradient><linearGradient id="iSNOo9d" x1="20.335" x2="20.88" y1="18.983" y2="19.439" gradientUnits="userSpaceOnUse"><stop class="cp95w770i"/><stop offset="1" class="dk3ah5owx"/></linearGradient><linearGradient id="iEIz0mc" x1="20.672" x2="20.914" y1="26.703" y2="26.422" gradientUnits="userSpaceOnUse"><stop class="ewlg17b4k"/><stop offset="1" class="b5b0myb0o"/></linearGradient><radialGradient id="ijlHapb" cx="0" cy="0" r="1" gradientTransform="rotate(105.944 7.283 7.238)scale(6.02483 2.63146)" gradientUnits="userSpaceOnUse"><stop class="h97tp9b_f"/><stop offset="1" class="pz-dlr8ug"/></radialGradient><radialGradient id="iClzQjb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 15.865 23.496)" gradientUnits="userSpaceOnUse"><stop class="b49w_gb5k"/><stop offset="1" class="xj4f5pzei"/></radialGradient><radialGradient id="iOvRkTB" cx="0" cy="0" r="1" gradientTransform="rotate(76.079 -.2 .937)scale(4.74993 3.74633)" gradientUnits="userSpaceOnUse"><stop class="omlmzobrb"/><stop offset="1" class="yju33hb2y"/></radialGradient><radialGradient id="ilL4HGX" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.4089 5.11912 0 18.103 23.496)" gradientUnits="userSpaceOnUse"><stop class="dtxh-hbco"/><stop offset="1" class="in7-smbur"/></radialGradient><radialGradient id="izNVhmg" cx="0" cy="0" r="1" gradientTransform="rotate(-45 34.16 1.731)scale(8.65467 3.14404)" gradientUnits="userSpaceOnUse"><stop class="w6o4myf_b"/><stop offset="1" class="c8s6441kg"/></radialGradient><radialGradient id="ilma3Md" cx="0" cy="0" r="1" gradientTransform="matrix(4.15623 3.31253 -1.73902 2.18195 22.078 17.063)" gradientUnits="userSpaceOnUse"><stop class="cpbnylbqu"/><stop offset="1" class="bgm6-ubvx"/></radialGradient><filter id="iPVPZ1b" width=".65" height="8.419" x="24.44" y="16.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4086" stdDeviation=".125"/></filter><filter id="i4sIBDe" width="5.65" height="6.709" x="10.725" y="16.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4086" stdDeviation=".125"/></filter><filter id="iAWdk2t" width="6.934" height="13.95" x="17.266" y="4.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4086" stdDeviation=".75"/></filter><filter id="ia0uKCF" width="8.303" height="18.853" x="9.476" y="4.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4086" stdDeviation=".75"/></filter><filter id="iSKNrte" width="3.928" height="4.044" x="17.885" y="1.792" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4086" stdDeviation=".5"/></filter><filter id="ibMHgnc" width="3.753" height="3.85" x="13.579" y="1.93" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4086" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:folded-hands-medium-light" /></template>
<style>
.aya86ob_i {
  d: path("M19.19 4.737c1.218 0 2.205.987 2.205 2.205v5.4a2 2 0 0 0 .69 1.512l2.33 2.018l-6.47 7.624l-.654-.635a.96.96 0 0 1-.303-.7v-4.094l-.004-.128V6.942c0-1.218.988-2.205 2.206-2.205");
}

.b1lbi7bol {
  stop-color: var(--svg-color--945bcc, #945BCC);
}

.b49w_gb5k {
  stop-color: var(--svg-color--a35a7a, #A35A7A);
}

.b5b0myb0o {
  stop-color: var(--svg-color--9469ff, #9469FF);
  stop-opacity: 0;
}

.b98qsobty {
  stop-color: var(--svg-color--fccca7, #FCCCA7);
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

.dtxh-hbco {
  stop-color: var(--svg-color--a0537c, #A0537C);
}

.e4xcmebwj {
  width: 4.39px;
  height: 8.125px;
  rx: 2.195px;
}

.ei0b1vpuw {
  stop-color: var(--svg-color--deac87, #DEAC87);
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

.fhsjt5paq {
  stop-color: var(--svg-color--a578ff, #A578FF);
}

.ft5dv1b6b {
  fill: none;
}

.gbq2iq9ef {
  stop-color: var(--svg-color--f6c8a5, #F6C8A5);
  stop-opacity: 0;
}

.h-3wzkb3q {
  stop-color: var(--svg-color--ba7d5e, #BA7D5E);
  stop-opacity: 0;
}

.h97tp9b_f {
  stop-color: var(--svg-color--e5bb95, #E5BB95);
}

.hx5258b2u {
  stop-color: var(--svg-color--fccea6, #FCCEA6);
  stop-opacity: 0;
}

.idp81whyl {
  stop-color: var(--svg-color--fccea6, #FCCEA6);
}

.ikko89bda {
  stop-color: var(--svg-color--cc9080, #CC9080);
}

.in7-smbur {
  stop-color: var(--svg-color--a0537c, #A0537C);
  stop-opacity: 0;
}

.j8pwmbb_m {
  stop-color: var(--svg-color--9867f8, #9867F8);
}

.juw1kcb0o {
  stop-color: var(--svg-color--d7a381, #D7A381);
}

.k03uj4bcp {
  stop-color: var(--svg-color--573eff, #573EFF);
}

.ki9m_gb7k {
  stop-color: var(--svg-color--6236ae, #6236AE);
  stop-opacity: 0;
}

.kwu0ecbgx {
  d: path("M14.779 4.737a2.206 2.206 0 0 0-2.206 2.205v5.4a2 2 0 0 1-.69 1.512l-2.33 2.018l6.47 7.624l.654-.635a1 1 0 0 0 .323-.713c-.024-5.068-.016-10.137-.016-15.206a2.206 2.206 0 0 0-2.206-2.205");
}

.n418v0b3f {
  d: path("m17.323 22.903l6.287-7.494a.6.6 0 0 1 .821-.093l.358.27a1 1 0 0 1 .398.799V29.74a.25.25 0 0 1-.41.192l-7.38-6.184a.6.6 0 0 1-.074-.846");
}

.not7hp43l {
  stop-color: var(--svg-color--f6c8a5, #F6C8A5);
}

.omlmzobrb {
  stop-color: var(--svg-color--efc49d, #EFC49D);
}

.opu5b_bed {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
}

.p5ok_v3pi {
  stop-color: var(--svg-color--fccca7, #FCCCA7);
}

.p5r1espwo {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M24.765 17.143v7.92");
}

.pz-dlr8ug {
  stop-color: var(--svg-color--cd9876, #CD9876);
}

.q9gpy7bkq {
  stop-color: var(--svg-color--6640a2, #6640A2);
}

.qxwbxgb_x {
  d: path("M14.147 6.66a1.066 1.066 0 0 1 2.132 0v12.503a2.284 2.284 0 0 1-4.272 1.124l-.643-1.137a3 3 0 0 1 .46-3.567l1.758-1.81a2 2 0 0 0 .565-1.393z");
}

.r2u3ribwc {
  cx: 19.849px;
  cy: 3.814px;
  rx: 0.828px;
  ry: 1.134px;
}

.sidzksbew {
  stop-color: var(--svg-color--a5704d, #A5704D);
  stop-opacity: 0;
}

.t2er4acdn {
  stop-color: var(--svg-color--9c6eff, #9C6EFF);
  stop-opacity: 0;
}

.tkn2a3_jz {
  stop-color: var(--svg-color--9f6640, #9F6640);
  stop-opacity: 0;
}

.tn-0g6vdf {
  cx: 15.456px;
  cy: 3.855px;
  fill: var(--svg-color--f3c6a1, #F3C6A1);
  rx: 0.764px;
  ry: 1.019px;
}

.ty0tbvbnm {
  stop-color: var(--svg-color--ba7d5e, #BA7D5E);
}

.tyfxpdb0w {
  stop-color: var(--svg-color--6236ae, #6236AE);
}

.w6o4myf_b {
  stop-color: var(--svg-color--8253ff, #8253FF);
}

.w9048gbal {
  stop-color: var(--svg-color--9f6640, #9F6640);
}

.wci41ibjf {
  stop-color: var(--svg-color--9a69fb, #9A69FB);
  stop-opacity: 0;
}

.xj4f5pzei {
  stop-color: var(--svg-color--a35a7a, #A35A7A);
  stop-opacity: 0;
}

.xl55w_row {
  stop-color: var(--svg-color--a5704d, #A5704D);
}

.yju33hb2y {
  stop-color: var(--svg-color--cc9973, #CC9973);
}

.z-fmvxbyg {
  stop-color: var(--svg-color--d2997f, #D2997F);
}

</style>
