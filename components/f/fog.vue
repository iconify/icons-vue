<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iPguL6c)" class="vbc9yyfud"/><path fill="url(#ikHb0ze)" class="vbc9yyfud"/><g filter="url(#isf5MNc)"><path fill="url(#iOrwgBd)" class="tqh7hyb7e"/></g><path fill="url(#ieHgKUc)" class="fat49en5n"/><path fill="url(#ijHooac)" class="fat49en5n"/><g filter="url(#itvw7se)"><path fill="url(#iO0R4ae)" class="ak7zl84gh"/><path fill="url(#iBUrMmP)" class="ak7zl84gh"/><path fill="url(#iJUz6Ys)" class="ak7zl84gh"/></g><g clip-rule="evenodd" filter="url(#iTT7Lfc)" class="d2kvgvbvc"><path fill="url(#iK5gvbb)" class="dg1ps7gvg"/><path fill="url(#ildT7gd)" class="dg1ps7gvg"/></g><g filter="url(#ivqIGpb)"><path fill="url(#iMn6wmb)" class="tswxskqfb"/><path fill="url(#iHmvmSc)" class="tswxskqfb"/></g><g filter="url(#ia4FoXc)"><path fill="url(#icMceAe)" class="dq4lrw2ab"/><path fill="url(#icdhJPc)" class="dq4lrw2ab"/></g><defs><radialGradient id="ikHb0ze" cx="0" cy="0" r="1" gradientTransform="rotate(-147.482 9.14 1.573)scale(5.9296)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="g2b9qygbx"/><stop offset="1" class="b7m30ubwm"/></radialGradient><radialGradient id="iOrwgBd" cx="0" cy="0" r="1" gradientTransform="matrix(-10 12.31246 -10.5418 -8.5619 29.25 4.125)" gradientUnits="userSpaceOnUse"><stop class="tnqmrf36g"/><stop offset="1" class="lxrvxe85b"/></radialGradient><radialGradient id="ieHgKUc" cx="0" cy="0" r="1" gradientTransform="rotate(130.888 3.366 4.84)scale(6.43018 5.67211)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="sd54lzbcr"/></radialGradient><radialGradient id="ijHooac" cx="0" cy="0" r="1" gradientTransform="rotate(-103.925 8.995 1.678)scale(3.89574 5.93314)" gradientUnits="userSpaceOnUse"><stop offset=".175" class="l__3lzboo"/><stop offset="1" class="jqewvl9-d"/></radialGradient><radialGradient id="iO0R4ae" cx="0" cy="0" r="1" gradientTransform="rotate(124.276 9.715 10.893)scale(15.7807)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="vc--wpv5i"/><stop offset="1" class="dwhq0gbya"/></radialGradient><radialGradient id="iBUrMmP" cx="0" cy="0" r="1" gradientTransform="rotate(-112.286 18.938 3.463)scale(4.83036)" gradientUnits="userSpaceOnUse"><stop class="jb02ok5yf"/><stop offset="1" class="yp2xafbst"/></radialGradient><radialGradient id="iJUz6Ys" cx="0" cy="0" r="1" gradientTransform="rotate(-163.083 11.818 5.792)scale(14.2519 14.4327)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="bh2nw2gqw"/><stop offset="1" class="j4yqjz3zd"/></radialGradient><radialGradient id="iK5gvbb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.2738 16.62373 -29.79628 -14.82991 12.15 14.178)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="t7gp9pb7z"/></radialGradient><radialGradient id="ildT7gd" cx="0" cy="0" r="1" gradientTransform="rotate(133.418 -1.677 14.561)scale(7.38188 4.8547)" gradientUnits="userSpaceOnUse"><stop offset=".267" class="t1iy6rbvl"/><stop offset="1" class="foqqic2ts"/></radialGradient><radialGradient id="iMn6wmb" cx="0" cy="0" r="1" gradientTransform="rotate(114.066 8.618 19.057)scale(8.56274 8.81777)" gradientUnits="userSpaceOnUse"><stop class="arei75b3o"/><stop offset="1" class="ejj09mbxc"/></radialGradient><radialGradient id="iHmvmSc" cx="0" cy="0" r="1" gradientTransform="matrix(1.89768 -7.45305 6.2165 1.58283 27.103 30.953)" gradientUnits="userSpaceOnUse"><stop class="bi0t_ybav"/><stop offset="1" class="qm_5k7nbn"/></radialGradient><radialGradient id="icMceAe" cx="0" cy="0" r="1" gradientTransform="rotate(128.726 5.877 15.702)scale(14.5091 15.3865)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="gxho33edf"/></radialGradient><filter id="isf5MNc" width="16.1" height="18.688" x="14" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.878431 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15305"/></filter><filter id="itvw7se" width="22.76" height="22.66" x="6.01" y="6.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.878431 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15305"/></filter><filter id="iTT7Lfc" width="14.1" height="20" x="2" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.878431 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15305"/></filter><filter id="ivqIGpb" width="10.943" height="13" x="19.157" y="17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.878431 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15305"/></filter><filter id="ia4FoXc" width="22.1" height="11" x="5" y="19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.882353 0 0 0 0 0.878431 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15305"/></filter><linearGradient id="iPguL6c" x1="16" x2="16" y1="2" y2="6.938" gradientUnits="userSpaceOnUse"><stop class="x47c7-_5u"/><stop offset="1" class="e7_774bmk"/></linearGradient><linearGradient id="icdhJPc" x1="15.565" x2="15.565" y1="32.775" y2="28.296" gradientUnits="userSpaceOnUse"><stop class="b7j_bzbmf"/><stop offset="1" class="iryi4pivu"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:fog" /></template>
<style>
.ak7zl84gh {
  d: path("M17.34 28.67c6.257 0 11.33-5.073 11.33-11.33S23.597 6.01 17.34 6.01S6.01 11.083 6.01 17.34s5.073 11.33 11.33 11.33");
}

.arei75b3o {
  stop-color: var(--svg-color--f4f3fb, #F4F3FB);
}

.b7j_bzbmf {
  stop-color: var(--svg-color--e3ddfb, #E3DDFB);
}

.b7m30ubwm {
  stop-color: var(--svg-color--dcdcdf, #DCDCDF);
  stop-opacity: 0;
}

.bh2nw2gqw {
  stop-color: var(--svg-color--e2e2e3, #E2E2E3);
  stop-opacity: 0;
}

.bi0t_ybav {
  stop-color: var(--svg-color--e5defd, #E5DEFD);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dg1ps7gvg {
  d: path("M11.999 30H5.67C3.64 30 2 28.36 2 26.33V10.61c1.1-.39 2.27-.61 3.5-.61C11.3 10 16 14.7 16 20.5c0 1.23-.22 2.4-.61 3.5z");
}

.dq4lrw2ab {
  d: path("M16 19C9.95 19 5.03 23.89 5 29.94c.22.04.44.06.67.06h20.66c.23 0 .45-.02.67-.06C26.97 23.89 22.06 19 16 19");
}

.dwhq0gbya {
  stop-color: var(--svg-color--e8e8ea, #E8E8EA);
}

.e7_774bmk {
  stop-color: var(--svg-color--e5e4e8, #E5E4E8);
}

.ejj09mbxc {
  stop-color: var(--svg-color--e2e2e5, #E2E2E5);
}

.fat49en5n {
  d: path("M6.91 2H5.67C3.64 2 2 3.64 2 5.67V13h11c0-4.64-2.44-8.7-6.09-11");
}

.foqqic2ts {
  stop-color: var(--svg-color--dbd9e4, #DBD9E4);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g2b9qygbx {
  stop-color: var(--svg-color--dcdcdf, #DCDCDF);
}

.gxho33edf {
  stop-color: var(--svg-color--e2e0ea, #E2E0EA);
}

.iryi4pivu {
  stop-color: var(--svg-color--e3ddfb, #E3DDFB);
  stop-opacity: 0;
}

.j4yqjz3zd {
  stop-color: var(--svg-color--e2e2e3, #E2E2E3);
}

.jb02ok5yf {
  stop-color: var(--svg-color--e0dee8, #E0DEE8);
}

.jqewvl9-d {
  stop-color: var(--svg-color--e5e4e6, #E5E4E6);
  stop-opacity: 0;
}

.l__3lzboo {
  stop-color: var(--svg-color--e5e4e6, #E5E4E6);
}

.lxrvxe85b {
  stop-color: var(--svg-color--e4e4e5, #E4E4E5);
}

.qm_5k7nbn {
  stop-color: var(--svg-color--e5defd, #E5DEFD);
  stop-opacity: 0;
}

.sd54lzbcr {
  stop-color: var(--svg-color--edecf1, #EDECF1);
}

.t1iy6rbvl {
  stop-color: var(--svg-color--dbd9e4, #DBD9E4);
}

.t7gp9pb7z {
  stop-color: var(--svg-color--dfd8fc, #DFD8FC);
}

.tnqmrf36g {
  stop-color: var(--svg-color--fbfafe, #FBFAFE);
}

.tqh7hyb7e {
  d: path("M26.33 2h-5.77A12.49 12.49 0 0 0 14 13l16 7.688V5.67C30 3.65 28.36 2 26.33 2");
}

.tswxskqfb {
  d: path("M19.157 30h7.173c2.03 0 3.67-1.64 3.67-3.67V17c-4.42 0-8 3.58-8 8z");
}

.vbc9yyfud {
  d: path("M26.33 30H5.67C3.64 30 2 28.36 2 26.33V5.67C2 3.64 3.64 2 5.67 2h20.66C28.36 2 30 3.64 30 5.67v20.66c0 2.03-1.64 3.67-3.67 3.67");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.x47c7-_5u {
  stop-color: var(--svg-color--ecebef, #ECEBEF);
}

.yp2xafbst {
  stop-color: var(--svg-color--e0dee8, #E0DEE8);
  stop-opacity: 0;
}

</style>
