<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ivo7YDc)" class="jl81vn0ac"/><g filter="url(#iC8SUqd)"><path class="eefvfxb-i"/></g><g filter="url(#i7crwNd)"><path fill="url(#i5jGxBb)" clip-rule="evenodd" class="qdqw6ttlb"/></g><g filter="url(#imPoCBc)"><path fill="url(#icla2vd)" clip-rule="evenodd" class="a_e0mdb7b"/></g><path fill="url(#i9KQVHe)" clip-rule="evenodd" class="rc_wfob2r"/><path fill="url(#i2f0dLb)" clip-rule="evenodd" class="rc_wfob2r"/><path fill="url(#iaUtY1N)" clip-rule="evenodd" class="rc_wfob2r"/><path fill="url(#iydaVDb)" clip-rule="evenodd" class="rc_wfob2r"/><circle fill="url(#iBGlP0d)" class="gbt0nvxll"/><circle fill="url(#iZrX8hb)" class="gbt0nvxll"/><defs><linearGradient id="i5jGxBb" x1="24.511" x2="4.284" y1="4.013" y2="28.534" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><linearGradient id="icla2vd" x1="16.029" x2="16.029" y1="7.016" y2="17.011" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="i9KQVHe" x1="12.516" x2="15.422" y1="9.966" y2="14.999" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="i2f0dLb" x1="13.165" x2="14.031" y1="13.09" y2="12.59" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iydaVDb" x1="12.516" x2="12.875" y1="9.966" y2="10.588" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><radialGradient id="ivo7YDc" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.496 1.03)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="iaUtY1N" cx="0" cy="0" r="1" gradientTransform="matrix(2.86513 4.96255 -.70605 .40764 13.24 10.001)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="iBGlP0d" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.258 11.405)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iZrX8hb" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.43 10.822)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iC8SUqd" width="9.004" height="13.984" x="9.516" y="6.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13621" stdDeviation=".75"/></filter><filter id="i7crwNd" width="28.8" height="28.8" x="1.6" y="1.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13621"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13621" result="effect2_innerShadow_18_13621"/></filter><filter id="imPoCBc" width="2.6" height="9.995" x="15.029" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13621"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eleven-oclock" /></template>
<style>
.a_e0mdb7b {
  fill-rule: evenodd;
  d: path("M16.029 7.016a1 1 0 0 1 1 1v7.995a1 1 0 0 1-2 0V8.016a1 1 0 0 1 1-1");
}

.bcrad1bcg {
  stop-color: var(--svg-color--f74093, #F74093);
}

.boh6xxb-j {
  stop-color: var(--svg-color--3e1846, #3E1846);
  stop-opacity: 0;
}

.bqasmib2b {
  stop-color: var(--svg-color--3e1846, #3E1846);
}

.cvn-6ybtn {
  stop-color: var(--svg-color--bdbabf, #BDBABF);
}

.d77sr4b-b {
  stop-color: var(--svg-color--50375f, #50375F);
}

.eefvfxb-i {
  fill: var(--svg-color--c1bec4, #C1BEC4);
  d: path("M15.029 8.016a1 1 0 0 1 1 1v6.274A1.988 1.988 0 0 1 15.03 19a1.99 1.99 0 0 1-1.738-2.956l-2.143-3.712a1 1 0 1 1 1.732-1l1.147 1.986V9.016a1 1 0 0 1 1-1");
}

.ft5dv1b6b {
  fill: none;
}

.gbt0nvxll {
  cx: 16.031px;
  cy: 16.011px;
  r: 1.989px;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
}

.jl81vn0ac {
  d: path("M30 16c0 7.732-6.268 14-14 14S2 23.732 2 16S8.268 2 16 2s14 6.268 14 14");
}

.lb3ip72ql {
  stop-color: var(--svg-color--776f7f, #776F7F);
}

.mttz6pbyd {
  stop-color: var(--svg-color--6d6b70, #6D6B70);
}

.my1z1hkvz {
  stop-color: var(--svg-color--2e2840, #2E2840);
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.qdqw6ttlb {
  fill-rule: evenodd;
  d: path("M16 27c6.075 0 11-4.925 11-11S22.075 5 16 5S5 9.925 5 16s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14S23.732 2 16 2S2 8.268 2 16s6.268 14 14 14");
}

.rc_wfob2r {
  fill-rule: evenodd;
  d: path("M12.516 9.966a1 1 0 0 1 1.366.366l2.984 5.168a1 1 0 1 1-1.732 1l-2.984-5.168a1 1 0 0 1 .366-1.366");
}

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.vjrcszb_p {
  stop-color: var(--svg-color--32183d, #32183D);
}

.wdxszo23j {
  stop-color: var(--svg-color--f83f4c, #F83F4C);
}

.y_kzz0mys {
  stop-color: var(--svg-color--2e2840, #2E2840);
  stop-opacity: 0;
}

.yrrl0sboi {
  stop-color: var(--svg-color--776f7f, #776F7F);
  stop-opacity: 0;
}

.zl0yx4b_i {
  stop-color: var(--svg-color--2c3a65, #2C3A65);
}

</style>
