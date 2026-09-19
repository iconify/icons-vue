<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="nouwlmbfi"/><g filter="url(#iWLv9jb)"><ellipse fill="url(#i8hs3Zy)" transform="rotate(26.087 17.338 9.08)" class="r4xp77bwq"/></g><g filter="url(#iil29Rd)"><path fill="url(#iuYVCwc)" class="crbyzbt1f"/><path fill="url(#i2qG5Fc)" class="crbyzbt1f"/></g><g filter="url(#iraUctE)"><circle fill="url(#iTwJaib)" class="pwg4xob8q"/></g><path class="aje6vrj6g"/><circle fill="url(#inG2iRb)" class="m7rma2bnk"/><circle fill="url(#ifqHPHS)" class="m7rma2bnk"/><g filter="url(#ihBylXt)"><circle class="dq_mlo43w"/></g><g filter="url(#iwjQl3c)"><path fill="url(#iXxW0yc)" class="o5ihkcskr"/><path fill="url(#iB8Nfkb)" class="o5ihkcskr"/></g><path fill="url(#iOaw4Be)" class="o5ihkcskr"/><path fill="url(#iTrCByc)" class="o5ihkcskr"/><path fill="url(#iVtKkee)" class="o5ihkcskr"/><path fill="url(#iYo0ZQc)" class="o5ihkcskr"/><path fill="url(#ibJNjyd)" class="o5ihkcskr"/><g filter="url(#ia4W7eK)"><path stroke="url(#icmgcOc)" class="dq8karbsq"/></g><g filter="url(#iPx6hTw)"><path stroke="url(#icDJbzd)" class="m62ba_b5p"/></g><defs><radialGradient id="i8hs3Zy" cx="0" cy="0" r="1" gradientTransform="rotate(-90.156 15.517 -1.78)scale(8.19144 14.286)" gradientUnits="userSpaceOnUse"><stop offset=".415" class="r_u_h5b3s"/><stop offset=".848" class="n64k1un-r"/></radialGradient><radialGradient id="ifqHPHS" cx="0" cy="0" r="1" gradientTransform="rotate(146.004 4.37 12.612)scale(3.24158 3.7019)" gradientUnits="userSpaceOnUse"><stop class="t5l7i-35d"/><stop offset="1" class="adrn92bkz"/></radialGradient><radialGradient id="iB8Nfkb" cx="0" cy="0" r="1" gradientTransform="matrix(3.875 -5.5625 6.22805 4.33864 17.5 10.83)" gradientUnits="userSpaceOnUse"><stop offset=".478" class="x6vt38irh"/><stop offset="1" class="tmjf1_bjl"/></radialGradient><radialGradient id="iOaw4Be" cx="0" cy="0" r="1" gradientTransform="matrix(.14338 -4.62474 6.13434 .19019 23.232 15.266)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="lz69ozbxw"/><stop offset="1" class="vze3y573s"/></radialGradient><radialGradient id="iTrCByc" cx="0" cy="0" r="1" gradientTransform="rotate(115.159 1.796 17.183)scale(4.97005 4.84669)" gradientUnits="userSpaceOnUse"><stop offset=".242" class="ugx2oqlqp"/><stop offset="1" class="pnq4imboc"/></radialGradient><radialGradient id="iVtKkee" cx="0" cy="0" r="1" gradientTransform="rotate(-115.896 19.594 6.144)scale(26.3315 19.1931)" gradientUnits="userSpaceOnUse"><stop offset=".953" class="ctwlg2kbz"/><stop offset="1" class="nooxnls9a"/></radialGradient><radialGradient id="iYo0ZQc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.14 21.87883 -17.0804 -2.45134 14.584 7.982)" gradientUnits="userSpaceOnUse"><stop offset=".912" class="iax6gzb3y"/><stop offset="1" class="nogxpdbja"/></radialGradient><radialGradient id="ibJNjyd" cx="0" cy="0" r="1" gradientTransform="matrix(2.09375 0 0 3.71875 10.344 22.142)" gradientUnits="userSpaceOnUse"><stop class="yegc_ubts"/><stop offset=".975" class="kjygdhcvm"/></radialGradient><linearGradient id="iuYVCwc" x1="12.875" x2="10.121" y1="12.579" y2="18.173" gradientUnits="userSpaceOnUse"><stop class="b00s7bcmy"/><stop offset="1" class="if_yphb0b"/></linearGradient><linearGradient id="i2qG5Fc" x1="13.563" x2="15.563" y1="27.517" y2="21.923" gradientUnits="userSpaceOnUse"><stop offset=".218" class="gips64bhy"/><stop offset="1" class="uf4yr6jab"/></linearGradient><linearGradient id="iTwJaib" x1="14.641" x2="12.533" y1="20.53" y2="24.242" gradientUnits="userSpaceOnUse"><stop offset=".34" class="idibcljtc"/><stop offset="1" class="a0x44vbjn"/></linearGradient><linearGradient id="inG2iRb" x1="11.755" x2="11.755" y1="19.142" y2="25.142" gradientUnits="userSpaceOnUse"><stop class="lx_jvtb1l"/><stop offset="1" class="on-xd39ns"/></linearGradient><linearGradient id="iXxW0yc" x1="11.563" x2="20" y1="31.517" y2="-.858" gradientUnits="userSpaceOnUse"><stop class="bmggupupr"/><stop offset="1" class="wgpnrcbke"/></linearGradient><linearGradient id="icmgcOc" x1="24.971" x2="17.565" y1="11.235" y2="3.423" gradientUnits="userSpaceOnUse"><stop class="dpqjfnyxb"/><stop offset=".51" class="o06vv8bvy"/><stop offset="1" class="dpqjfnyxb"/></linearGradient><linearGradient id="icDJbzd" x1="8.313" x2="21.251" y1="2.017" y2="24.121" gradientUnits="userSpaceOnUse"><stop class="dpqjfnyxb"/><stop offset=".698" class="o06vv8bvy"/></linearGradient><filter id="iWLv9jb" width="15.705" height="12.527" x="9.486" y="2.817" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4615" stdDeviation=".5"/></filter><filter id="iil29Rd" width="12.531" height="17.719" x="7.531" y="11.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4615" stdDeviation=".25"/></filter><filter id="iraUctE" width="7.349" height="7.349" x="8.61" y="18.543" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4615" stdDeviation=".375"/></filter><filter id="ihBylXt" width="6.234" height="6.234" x="8.656" y="19.196" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4615" stdDeviation=".25"/></filter><filter id="iwjQl3c" width="19.085" height="27.786" x="6.708" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.6 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4615"/></filter><filter id="ia4W7eK" width="12.094" height="12.656" x="14.44" y="1.079" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4615" stdDeviation=".75"/></filter><filter id="iPx6hTw" width="13.063" height="22.313" x="6.813" y="7.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4615" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ear" /></template>
<style>
.a0x44vbjn {
  stop-color: var(--svg-color--c97a03, #C97A03);
}

.adrn92bkz {
  stop-color: var(--svg-color--ffe663, #FFE663);
  stop-opacity: 0;
}

.aje6vrj6g {
  stroke: var(--svg-color--000, #000);
  d: path("M17.5 3.298c1.927.27 5.975 1.95 6.75 6.5");
}

.b00s7bcmy {
  stop-color: var(--svg-color--e58403, #E58403);
}

.bmggupupr {
  stop-color: var(--svg-color--f0a130, #F0A130);
}

.crbyzbt1f {
  d: path("M12.577 28.735c-3.288-.25-4.546-2.063-4.546-5.304V12.173l2.344-.156l9.188 9.156l-2.938 4.969c-.989 1.845-1.68 2.593-4.049 2.593");
}

.ctwlg2kbz {
  stop-color: var(--svg-color--cea561, #CEA561);
  stop-opacity: 0;
}

.dpqjfnyxb {
  stop-color: var(--svg-color--ffed65, #FFED65);
  stop-opacity: 0;
}

.dq_mlo43w {
  cx: 11.774px;
  cy: 22.313px;
  r: 2.617px;
  fill: var(--svg-color--ffc947, #FFC947);
}

.dq8karbsq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.94 3.58c2.291.374 6.919 2.43 7.094 7.655");
}

.ft5dv1b6b {
  fill: none;
}

.gips64bhy {
  stop-color: var(--svg-color--e2992f, #E2992F);
}

.iax6gzb3y {
  stop-color: var(--svg-color--d98286, #D98286);
  stop-opacity: 0;
}

.idibcljtc {
  stop-color: var(--svg-color--ffe15b, #FFE15B);
}

.if_yphb0b {
  stop-color: var(--svg-color--e58403, #E58403);
  stop-opacity: 0;
}

.kjygdhcvm {
  stop-color: var(--svg-color--ffcd49, #FFCD49);
  stop-opacity: 0;
}

.lx_jvtb1l {
  stop-color: var(--svg-color--ffc609, #FFC609);
}

.lz69ozbxw {
  stop-color: var(--svg-color--ffcc4c, #FFCC4C);
}

.m62ba_b5p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.063 10.235v13.657c.021.895.333 3.408 3.062 4.03c2.297.525 3.625-.687 4.275-1.905l1.225-2.125");
}

.m7rma2bnk {
  cx: 11.755px;
  cy: 22.142px;
  r: 3px;
}

.n64k1un-r {
  stop-color: var(--svg-color--ee8820, #EE8820);
}

.nogxpdbja {
  stop-color: var(--svg-color--d98286, #D98286);
}

.nooxnls9a {
  stop-color: var(--svg-color--cea561, #CEA561);
}

.nouwlmbfi {
  fill: var(--svg-color--ffc94c, #FFC94C);
  d: path("M6.708 23.43c0 3.242 2.581 6.18 5.868 6.431c2.37 0 4.459-1.374 5.447-3.22l5.756-10.19a9.292 9.292 0 1 0-17.072-5.084z");
}

.o06vv8bvy {
  stop-color: var(--svg-color--ffed65, #FFED65);
}

.o5ihkcskr {
  d: path("M18.167 22.696a1.8 1.8 0 0 0-2.439.69l-.859 1.52l-.018.035c-.366.682-1.156 1.316-2.135 1.316c-1.255 0-2.408-1.428-2.408-2.826V11.367a5.692 5.692 0 1 1 11.315.891c-.147.94.126 1.974.943 2.46c.9.537 2.084.21 2.37-.797a9.292 9.292 0 1 0-18.23-2.554v12.064c.002 3.24 2.583 6.18 5.87 6.43c2.37 0 4.459-1.374 5.447-3.22l.84-1.485a1.8 1.8 0 0 0-.696-2.46");
}

.on-xd39ns {
  stop-color: var(--svg-color--fea70c, #FEA70C);
}

.pnq4imboc {
  stop-color: var(--svg-color--ffca4d, #FFCA4D);
  stop-opacity: 0;
}

.pwg4xob8q {
  cx: 12.284px;
  cy: 22.218px;
  r: 2.924px;
}

.r_u_h5b3s {
  stop-color: var(--svg-color--ee8820, #EE8820);
  stop-opacity: 0;
}

.r4xp77bwq {
  cx: 17.338px;
  cy: 9.081px;
  rx: 7.28px;
  ry: 4.652px;
}

.t5l7i-35d {
  stop-color: var(--svg-color--ffe663, #FFE663);
}

.tmjf1_bjl {
  stop-color: var(--svg-color--f49419, #F49419);
  stop-opacity: 0;
}

.uf4yr6jab {
  stop-color: var(--svg-color--e2992f, #E2992F);
  stop-opacity: 0;
}

.ugx2oqlqp {
  stop-color: var(--svg-color--ffca4d, #FFCA4D);
}

.vze3y573s {
  stop-color: var(--svg-color--ffcc4c, #FFCC4C);
  stop-opacity: 0;
}

.wgpnrcbke {
  stop-color: var(--svg-color--ffd135, #FFD135);
}

.x6vt38irh {
  stop-color: var(--svg-color--f49419, #F49419);
}

.yegc_ubts {
  stop-color: var(--svg-color--ffcd49, #FFCD49);
}

</style>
