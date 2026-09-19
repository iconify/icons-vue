<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i05QBNe)" class="a5awa9dpy"/><g filter="url(#iqUTa4b)"><path class="w5v6a_byu"/></g><g filter="url(#ibDHm7d)"><path fill="url(#ipxkXlV)" clip-rule="evenodd" class="uxc0mj8_i"/></g><path fill="url(#iepJsid)" clip-rule="evenodd" class="jt1ukbc_e"/><path fill="url(#ixaTuLd)" clip-rule="evenodd" class="jt1ukbc_e"/><path fill="url(#i7FeNxe)" clip-rule="evenodd" class="jt1ukbc_e"/><path fill="url(#iuB1vKb)" clip-rule="evenodd" class="jt1ukbc_e"/><g filter="url(#iffMOtL)"><path fill="url(#iShdZse)" clip-rule="evenodd" class="edywn_bhv"/></g><path fill="url(#i7UDhUS)" class="ain1pzbin"/><path fill="url(#iDb5Jod)" class="ain1pzbin"/><defs><linearGradient id="ipxkXlV" x1="16.029" x2="16.029" y1="7.027" y2="17.022" gradientUnits="userSpaceOnUse"><stop class="wdxszo23j"/><stop offset="1" class="bcrad1bcg"/></linearGradient><linearGradient id="iepJsid" x1="9.995" x2="15.028" y1="19.506" y2="16.6" gradientUnits="userSpaceOnUse"><stop class="vjrcszb_p"/><stop offset="1" class="zl0yx4b_i"/></linearGradient><linearGradient id="ixaTuLd" x1="13.119" x2="12.619" y1="18.857" y2="17.991" gradientUnits="userSpaceOnUse"><stop class="my1z1hkvz"/><stop offset="1" class="y_kzz0mys"/></linearGradient><linearGradient id="iuB1vKb" x1="9.995" x2="10.617" y1="19.506" y2="19.147" gradientUnits="userSpaceOnUse"><stop class="bqasmib2b"/><stop offset="1" class="boh6xxb-j"/></linearGradient><linearGradient id="iShdZse" x1="24.511" x2="4.284" y1="4.025" y2="28.545" gradientUnits="userSpaceOnUse"><stop class="mttz6pbyd"/><stop offset="1" class="olhrobbtj"/></linearGradient><radialGradient id="i05QBNe" cx="0" cy="0" r="1" gradientTransform="rotate(-46.212 33.51 1.035)scale(25.2966)" gradientUnits="userSpaceOnUse"><stop offset=".598" class="to7kn6bnn"/><stop offset="1" class="cvn-6ybtn"/></radialGradient><radialGradient id="i7FeNxe" cx="0" cy="0" r="1" gradientTransform="rotate(-30 40.063 -9.326)scale(5.73026 .81528)" gradientUnits="userSpaceOnUse"><stop class="d77sr4b-b"/><stop offset="1" class="i61yhl-1u"/></radialGradient><radialGradient id="i7UDhUS" cx="0" cy="0" r="1" gradientTransform="rotate(134.039 5.255 11.41)scale(3.40442)" gradientUnits="userSpaceOnUse"><stop class="gzwdfjydy"/><stop offset="1" class="sb8wjubjk"/></radialGradient><radialGradient id="iDb5Jod" cx="0" cy="0" r="1" gradientTransform="rotate(139.399 5.427 10.827)scale(2.88111)" gradientUnits="userSpaceOnUse"><stop offset=".527" class="yrrl0sboi"/><stop offset="1" class="lb3ip72ql"/></radialGradient><filter id="iqUTa4b" width="11.159" height="15.979" x="7.736" y="6.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_13585" stdDeviation=".75"/></filter><filter id="ibDHm7d" width="2.6" height="9.995" x="15.029" y="7.027" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.635294 0 0 0 0 0.227451 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13585"/></filter><filter id="iffMOtL" width="28.8" height="28.8" x="1.6" y="1.611" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.282353 0 0 0 0 0.254902 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_13585"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_13585" result="effect2_innerShadow_18_13585"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:eight-oclock" /></template>
<style>
.a5awa9dpy {
  d: path("M30 16.011c0 7.732-6.268 14-14 14s-14-6.268-14-14s6.268-14 14-14s14 6.268 14 14");
}

.ain1pzbin {
  d: path("M18.02 16.022a1.989 1.989 0 1 1-3.978 0a1.989 1.989 0 0 1 3.978 0");
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

.edywn_bhv {
  fill-rule: evenodd;
  d: path("M16 27.011c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11m0 3c7.732 0 14-6.268 14-14s-6.268-14-14-14s-14 6.268-14 14s6.268 14 14 14");
}

.ft5dv1b6b {
  fill: none;
}

.gzwdfjydy {
  stop-color: var(--svg-color--c9c6cc, #C9C6CC);
}

.i61yhl-1u {
  stop-color: var(--svg-color--50375f, #50375F);
  stop-opacity: 0;
}

.jt1ukbc_e {
  fill-rule: evenodd;
  d: path("M9.995 19.506a1 1 0 0 1 .366-1.366l5.168-2.984a1 1 0 1 1 1 1.732l-5.168 2.984a1 1 0 0 1-1.366-.366");
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

.sb8wjubjk {
  stop-color: var(--svg-color--928e95, #928E95);
}

.to7kn6bnn {
  stop-color: var(--svg-color--dddadf, #DDDADF);
}

.uxc0mj8_i {
  fill-rule: evenodd;
  d: path("M16.029 7.027a1 1 0 0 1 1 1v7.995a1 1 0 1 1-2 0V8.027a1 1 0 0 1 1-1");
}

.vjrcszb_p {
  stop-color: var(--svg-color--32183d, #32183D);
}

.w5v6a_byu {
  fill: var(--svg-color--c6c3c9, #C6C3C9);
  d: path("M15.404 7.783a1 1 0 0 1 1 1v6.274a1.988 1.988 0 0 1-1.988 3.446l-3.68 2.125a1 1 0 0 1-1-1.733l3.681-2.125c.003-.73.399-1.367.987-1.71V8.783a1 1 0 0 1 1-1");
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
