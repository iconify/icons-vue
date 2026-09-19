<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijIU6nZ)"><path fill="url(#i8YmTyc)" class="dsw8zq19a"/></g><path fill="url(#iGwyYPF)" class="dsw8zq19a"/><path fill="url(#isI9BZw)" class="dsw8zq19a"/><path fill="url(#ileyK0X)" class="dsw8zq19a"/><g filter="url(#iaorJyd)"><circle class="stod3oblt"/></g><circle fill="url(#iIrJx8j)" class="d_nkix9kd"/><g filter="url(#ieiczrb)"><circle class="s91b9bc6s"/></g><g filter="url(#ibn87Cb)"><path fill="url(#ipYtOve)" class="y-l-jjvye"/></g><g filter="url(#ibn87Cb)"><path fill="url(#ipYtOve)" class="y-l-jjvye"/></g><g filter="url(#iB4aWLb)"><path fill="url(#ipYtOve)" class="y-l-jjvye"/></g><path fill="url(#iYeJ2Xc)" class="j2msisgyx"/><path fill="url(#irdjIAc)" class="j2msisgyx"/><path fill="url(#ixlJBHc)" class="j2msisgyx"/><g filter="url(#iCnHGbd)"><rect fill="url(#im9X24d)" transform="rotate(-30 13.537 4.82)" class="x4s6pornd"/></g><defs><radialGradient id="isI9BZw" cx="0" cy="0" r="1" gradientTransform="matrix(-.43736 25.03128 -18.10474 -.31634 24.947 5.461)" gradientUnits="userSpaceOnUse"><stop offset=".932" class="nofhvlb1s"/><stop offset="1" class="uq3y0dbhe"/></radialGradient><radialGradient id="ileyK0X" cx="0" cy="0" r="1" gradientTransform="matrix(.625 .76562 -4.99204 4.07518 16.682 10.726)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="xi3zeebvm"/><stop offset=".927" class="mkapb1b_j"/></radialGradient><radialGradient id="ipYtOve" cx="0" cy="0" r="1" gradientTransform="matrix(-8.78131 5.7812 -4.54303 -6.9006 17.353 6.46)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="bcaikz0al"/><stop offset="1" class="ftwty2_4o"/></radialGradient><radialGradient id="iYeJ2Xc" cx="0" cy="0" r="1" gradientTransform="rotate(145.734 2.708 7.105)scale(3.28973 6.06771)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="ceaxyjbzu"/><stop offset="1" class="hb1e2bw8w"/></radialGradient><radialGradient id="irdjIAc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65622 7.0395 -7.43236 -2.80445 11.666 8.96)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="o2wg7pbxp"/><stop offset=".996" class="ahrjzupim"/></radialGradient><radialGradient id="ixlJBHc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03125 1.625 -.71032 -.45078 11.666 14.148)" gradientUnits="userSpaceOnUse"><stop offset=".202" class="v_30rnb-l"/><stop offset="1" class="oi0frbc7p"/></radialGradient><filter id="ijIU6nZ" width="17.61" height="28.567" x="10.269" y="2.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.254902 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23821"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.4" dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.447059 0 0 0 0 0.411765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23821" result="effect2_innerShadow_18_23821"/></filter><filter id="iaorJyd" width="2.741" height="2.741" x="23.498" y="26.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23821" stdDeviation=".15"/></filter><filter id="ieiczrb" width="2.203" height="2.203" x="23.814" y="26.578" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23821" stdDeviation=".125"/></filter><filter id="ibn87Cb" width="13.769" height="13.111" x="5.009" y="2.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.180392 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23821"/></filter><filter id="iB4aWLb" width="13.769" height="13.711" x="5.009" y="2.889" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.180392 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_23821"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.2 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_23821" result="effect2_innerShadow_18_23821"/></filter><filter id="iCnHGbd" width="6.242" height="7.899" x="12.879" y="3.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_23821" stdDeviation=".375"/></filter><linearGradient id="i8YmTyc" x1="12.634" x2="24.697" y1="4.023" y2="24.898" gradientUnits="userSpaceOnUse"><stop class="fdphgdctx"/><stop offset="1" class="ezxpi4hjw"/></linearGradient><linearGradient id="iGwyYPF" x1="11.916" x2="12.478" y1="2.867" y2="3.492" gradientUnits="userSpaceOnUse"><stop class="ve4xjcv8h"/><stop offset="1" class="kuviqnbjw"/></linearGradient><linearGradient id="iIrJx8j" x1="25.759" x2="24.431" y1="26.82" y2="28.617" gradientUnits="userSpaceOnUse"><stop class="jaeouuvbx"/><stop offset=".634" class="ann3vj0-b"/><stop offset="1" class="ek4nr7baq"/></linearGradient><linearGradient id="im9X24d" x1="15.872" x2="13.027" y1="7.923" y2="8.231" gradientUnits="userSpaceOnUse"><stop class="uyhrkfpbu"/><stop offset="1" class="jxga03esb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:axe" /></template>
<style>
.ahrjzupim {
  stop-color: var(--svg-color--aa82c9, #AA82C9);
}

.ann3vj0-b {
  stop-color: var(--svg-color--b1a4b1, #B1A4B1);
}

.bcaikz0al {
  stop-color: var(--svg-color--fc3f8e, #FC3F8E);
}

.ceaxyjbzu {
  stop-color: var(--svg-color--bfb2ca, #BFB2CA);
}

.d_nkix9kd {
  cx: 24.916px;
  cy: 27.679px;
  r: 1.07px;
}

.dsw8zq19a {
  d: path("M13.547 2.875a.8.8 0 0 0-1.093-.292l-1.385.8a.8.8 0 0 0-.293 1.092l11.326 19.617c.598 1.037.251 2.39.251 3.587a2.563 2.563 0 1 0 4.685-1.437z");
}

.ek4nr7baq {
  stop-color: var(--svg-color--a987c0, #A987C0);
}

.ezxpi4hjw {
  stop-color: var(--svg-color--795055, #795055);
}

.fdphgdctx {
  stop-color: var(--svg-color--825a51, #825A51);
}

.ft5dv1b6b {
  fill: none;
}

.ftwty2_4o {
  stop-color: var(--svg-color--f63b62, #F63B62);
}

.hb1e2bw8w {
  stop-color: var(--svg-color--ae98af, #AE98AF);
}

.j2msisgyx {
  d: path("M12.007 14.351a5 5 0 0 0-.65 1.042c-.183.38-.556.651-.974.6a6.118 6.118 0 0 1-4.846-8.56c.16-.358.541-.543.932-.515c.4.03.81.04 1.23-.014c-.904 1.072-1.863 3.127-.533 5.369c1.176 1.983 3.369 2.218 4.84 2.078");
}

.jaeouuvbx {
  stop-color: var(--svg-color--e7e2ec, #E7E2EC);
}

.jxga03esb {
  stop-color: var(--svg-color--ff63af, #FF63AF);
  stop-opacity: 0;
}

.kuviqnbjw {
  stop-color: var(--svg-color--7b5447, #7B5447);
  stop-opacity: 0;
}

.mkapb1b_j {
  stop-color: var(--svg-color--723643, #723643);
  stop-opacity: 0;
}

.nofhvlb1s {
  stop-color: var(--svg-color--68305b, #68305B);
  stop-opacity: 0;
}

.o2wg7pbxp {
  stop-color: var(--svg-color--aa82c9, #AA82C9);
  stop-opacity: 0;
}

.oi0frbc7p {
  stop-color: var(--svg-color--d0c1df, #D0C1DF);
  stop-opacity: 0;
}

.s91b9bc6s {
  cx: 24.916px;
  cy: 27.679px;
  r: 0.852px;
  fill: var(--svg-color--d0c2df, #D0C2DF);
}

.stod3oblt {
  cx: 24.869px;
  cy: 27.718px;
  r: 1.07px;
  fill: var(--svg-color--6c424d, #6C424D);
}

.uq3y0dbhe {
  stop-color: var(--svg-color--68305b, #68305B);
}

.uyhrkfpbu {
  stop-color: var(--svg-color--ff63af, #FF63AF);
}

.v_30rnb-l {
  stop-color: var(--svg-color--d0c1df, #D0C1DF);
}

.ve4xjcv8h {
  stop-color: var(--svg-color--7b5447, #7B5447);
}

.x4s6pornd {
  width: 1.948px;
  height: 6.476px;
  x: 13.537px;
  y: 4.819px;
  rx: 0.25px;
}

.xi3zeebvm {
  stop-color: var(--svg-color--723643, #723643);
}

.y-l-jjvye {
  d: path("M13.995 12.789c-.4.247-1.129.723-1.782 1.343c-.35.332-.638.807-.857 1.261c-.182.38-.555.651-.973.6a6.118 6.118 0 0 1-4.846-8.56c.16-.358.541-.543.932-.515c.852.063 1.75.038 2.697-.504q.12-.068.256-.134l4.995-2.884a.8.8 0 0 1 1.093.293l3.162 5.476a.8.8 0 0 1-.293 1.093z");
}

</style>
