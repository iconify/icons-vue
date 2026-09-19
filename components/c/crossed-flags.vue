<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ioaFf7c)"><path class="y5sqwzbee"/></g><g filter="url(#inKvOWc)"><path class="gao1n6_2o"/></g><g filter="url(#iD9KYpe)"><path fill="url(#ig4GOId)" class="g-pg-kewb"/><path fill="url(#ifq08kc)" class="g-pg-kewb"/></g><g filter="url(#i8MiF4S)"><path class="hpmahwb5l"/></g><path class="gvuackb5t"/><path fill="url(#ifzwzXd)" class="pv9yb36dq"/><path fill="url(#iHWdGqe)" class="pv9yb36dq"/><path fill="url(#i3Tmbmd)" class="pv9yb36dq"/><path fill="url(#ikSG5WN)" class="pv9yb36dq"/><g filter="url(#iFn7wtd)"><path class="rxe3dvbiw"/></g><g filter="url(#iLKDxbN)"><path class="fhs-srb9k"/></g><circle class="w-fs0umal"/><circle fill="url(#iQqYt6b)" class="vpexsgv1o"/><g filter="url(#idvTtBb)"><path class="vbwk48lrs"/></g><g filter="url(#iNZgU2c)"><path class="ecyk28b4y"/><path fill="url(#iNqyIBd)" class="z5mn73yxe"/><path fill="url(#iL8YEqc)" class="z5mn73yxe"/></g><g filter="url(#itHzUcd)"><path class="kewstf_sb"/><path fill="url(#iOKumed)" class="aw5ig8b4u"/><path fill="url(#iaCYQKb)" class="aw5ig8b4u"/><path fill="url(#ih6MDHc)" class="aw5ig8b4u"/></g><circle transform="matrix(-1 0 0 1 23.358 13.447)" class="d6v8_ibqs"/><circle fill="url(#iNvjBDk)" transform="matrix(-1 0 0 1 23.358 13.447)" class="mv2vusb4x"/><defs><linearGradient id="ig4GOId" x1="6.684" x2="8.778" y1="21.838" y2="15.619" gradientUnits="userSpaceOnUse"><stop offset=".066" class="wd-pmobbk"/><stop offset="1" class="t2wui94jw"/></linearGradient><linearGradient id="ifq08kc" x1="9.465" x2="6.403" y1="18.744" y2="19.994" gradientUnits="userSpaceOnUse"><stop offset=".374" class="o-dx3bbak"/><stop offset="1" class="zvj0vmb3h"/></linearGradient><linearGradient id="ifzwzXd" x1="7.621" x2="8.871" y1="15.744" y2="15.15" gradientUnits="userSpaceOnUse"><stop offset=".559" class="p0-igtb9f"/><stop offset="1" class="samx7hpzs"/></linearGradient><linearGradient id="iHWdGqe" x1="7.84" x2="7.981" y1="7.361" y2="7.658" gradientUnits="userSpaceOnUse"><stop class="wstr51vhg"/><stop offset=".994" class="hop683bux"/></linearGradient><linearGradient id="i3Tmbmd" x1="12.645" x2="12.52" y1="16.611" y2="16.346" gradientUnits="userSpaceOnUse"><stop class="rjqk0f4sw"/><stop offset="1" class="hb-v1ibbv"/></linearGradient><linearGradient id="ikSG5WN" x1="15.278" x2="14.528" y1="12.494" y2="12.854" gradientUnits="userSpaceOnUse"><stop offset=".391" class="vc--wpv5i"/><stop offset="1" class="csogkqfmg"/></linearGradient><linearGradient id="iQqYt6b" x1="7.496" x2="8.324" y1="14.51" y2="14.072" gradientUnits="userSpaceOnUse"><stop offset=".198" class="svn_nlb1i"/><stop offset="1" class="n0jf4lb6a"/></linearGradient><linearGradient id="iNqyIBd" x1="23.309" x2="23.153" y1="17.963" y2="19.588" gradientUnits="userSpaceOnUse"><stop class="azmrtxbft"/><stop offset="1" class="j-efl5b-c"/></linearGradient><linearGradient id="iL8YEqc" x1="23.5" x2="23.2" y1="19.404" y2="19.268" gradientUnits="userSpaceOnUse"><stop class="fm0uxeboe"/><stop offset="1" class="p66l76blk"/></linearGradient><linearGradient id="iOKumed" x1="25.551" x2="24.02" y1="15.744" y2="15.025" gradientUnits="userSpaceOnUse"><stop offset=".271" class="k0iunxzjd"/><stop offset="1" class="adngw-bnk"/></linearGradient><linearGradient id="iaCYQKb" x1="18.77" x2="19.551" y1="10.4" y2="10.744" gradientUnits="userSpaceOnUse"><stop offset=".099" class="oa7-35axz"/><stop offset="1" class="qz53z_d5t"/></linearGradient><linearGradient id="ih6MDHc" x1="20.395" x2="20.691" y1="16.713" y2="16.104" gradientUnits="userSpaceOnUse"><stop class="hunmi-f3n"/><stop offset="1" class="azm39lm3y"/></linearGradient><linearGradient id="iNvjBDk" x1=".158" x2="1.221" y1="3.719" y2="3.188" gradientUnits="userSpaceOnUse"><stop offset=".482" class="dk-_cj9jp"/><stop offset="1" class="yy3okbctu"/></linearGradient><filter id="ioaFf7c" width="11.785" height="23.801" x="10.227" y="3.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.439216 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/></filter><filter id="inKvOWc" width="11.135" height="23.151" x="10.622" y="4.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4_7843" stdDeviation=".1"/></filter><filter id="iD9KYpe" width="8.48" height="11.123" x="2.788" y="11.214" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.670588 0 0 0 0 0.611765 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/></filter><filter id="i8MiF4S" width="2.478" height="3.752" x="8.691" y="17.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.67451 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/></filter><filter id="iFn7wtd" width="12.035" height="23.801" x="11.155" y="3.974" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.447059 0 0 0 0 0.439216 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/></filter><filter id="iLKDxbN" width="11.135" height="23.151" x="11.524" y="4.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4_7843" stdDeviation=".1"/></filter><filter id="idvTtBb" width="8.83" height="11.323" x="21.449" y="11.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.662745 0 0 0 0 0.8 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 1 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4_7843" result="effect2_innerShadow_4_7843"/></filter><filter id="iNZgU2c" width="2.628" height="3.752" x="21.749" y="17.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.666667 0 0 0 0 0.721569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/></filter><filter id="itHzUcd" width="10.702" height="12.73" x="16.789" y="5.741" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.960784 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4_7843"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-flags" /></template>
<style>
.adngw-bnk {
  stop-color: var(--svg-color--f0e6fa, #F0E6FA);
  stop-opacity: 0;
}

.aw5ig8b4u {
  d: path("m24.402 17.99l2.63-5.63a.437.437 0 0 0-.214-.581a.35.35 0 0 1-.173-.459l.76-1.723a1 1 0 0 0-.495-1.312l-5.435-2.508a.4.4 0 0 0-.529.193l-4.019 8.506a.4.4 0 0 0 .192.532l6.75 3.175a.4.4 0 0 0 .533-.193");
}

.azm39lm3y {
  stop-color: var(--svg-color--ad9dbe, #AD9DBE);
  stop-opacity: 0;
}

.azmrtxbft {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
}

.csogkqfmg {
  stop-color: var(--svg-color--ebe2f6, #EBE2F6);
  stop-opacity: 0;
}

.d6v8_ibqs {
  r: 2.266px;
  fill: var(--svg-color--dd3240, #DD3240);
}

.dk-_cj9jp {
  stop-color: var(--svg-color--e8333e, #E8333E);
}

.ecyk28b4y {
  fill: var(--svg-color--c7bcd2, #C7BCD2);
  d: path("m24.226 17.651l-1.087-.486l-1.355 3.029a.4.4 0 0 0 .201.528l.358.16a.4.4 0 0 0 .529-.202z");
}

.fhs-srb9k {
  stroke: var(--svg-color--b3b2b7, #B3B2B7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m22.36 4.584l-10.535 22.55");
}

.fm0uxeboe {
  stop-color: var(--svg-color--e5d9f2, #E5D9F2);
}

.ft5dv1b6b {
  fill: none;
}

.g-pg-kewb {
  d: path("M2.876 14.327a1 1 0 0 1 .504-1.321l3.781-1.692l3.972 8.88a.4.4 0 0 1-.202.528L7.515 22.25a1 1 0 0 1-1.32-.505z");
}

.gao1n6_2o {
  stroke: var(--svg-color--b3b2b7, #B3B2B7);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m10.922 4.584l10.535 22.55");
}

.gvuackb5t {
  fill: var(--svg-color--e5dcf0, #E5DCF0);
  d: path("m8.506 17.99l-2.629-5.63a.437.437 0 0 1 .213-.581a.35.35 0 0 0 .174-.459l-.761-1.723a1 1 0 0 1 .496-1.312l5.434-2.508a.4.4 0 0 1 .53.193l4.018 8.506a.4.4 0 0 1-.191.532l-6.751 3.175a.4.4 0 0 1-.533-.193");
}

.hb-v1ibbv {
  stop-color: var(--svg-color--bfb0cf, #BFB0CF);
  stop-opacity: 0;
}

.hop683bux {
  stop-color: var(--svg-color--c6c2ca, #C6C2CA);
  stop-opacity: 0;
}

.hpmahwb5l {
  fill: var(--svg-color--efe6f8, #EFE6F8);
  d: path("m8.69 17.651l1.088-.486l1.355 3.029a.4.4 0 0 1-.202.528l-.357.16a.4.4 0 0 1-.529-.202z");
}

.hunmi-f3n {
  stop-color: var(--svg-color--ad9dbe, #AD9DBE);
}

.j-efl5b-c {
  stop-color: var(--svg-color--b5a9bf, #B5A9BF);
  stop-opacity: 0;
}

.k0iunxzjd {
  stop-color: var(--svg-color--f0e6fa, #F0E6FA);
}

.kewstf_sb {
  fill: var(--svg-color--e5dbf0, #E5DBF0);
  d: path("m24.402 17.99l2.63-5.63a.437.437 0 0 0-.214-.581a.35.35 0 0 1-.173-.459l.76-1.723a1 1 0 0 0-.495-1.312l-5.435-2.508a.4.4 0 0 0-.529.193l-4.019 8.506a.4.4 0 0 0 .192.532l6.75 3.175a.4.4 0 0 0 .533-.193");
}

.mv2vusb4x {
  r: 2.266px;
}

.n0jf4lb6a {
  stop-color: var(--svg-color--b8232b, #B8232B);
  stop-opacity: 0;
}

.o-dx3bbak {
  stop-color: var(--svg-color--b2a3c1, #B2A3C1);
}

.oa7-35axz {
  stop-color: var(--svg-color--bab5be, #BAB5BE);
}

.p0-igtb9f {
  stop-color: var(--svg-color--baaec7, #BAAEC7);
}

.p66l76blk {
  stop-color: var(--svg-color--c7bcd2, #C7BCD2);
}

.pv9yb36dq {
  d: path("m8.506 17.99l-2.629-5.63a.437.437 0 0 1 .213-.581a.35.35 0 0 0 .174-.459l-.761-1.723a1 1 0 0 1 .496-1.312l5.434-2.508a.4.4 0 0 1 .53.193l4.018 8.506a.4.4 0 0 1-.191.532l-6.751 3.175a.4.4 0 0 1-.533-.193");
}

.qz53z_d5t {
  stop-color: var(--svg-color--dbd1e6, #DBD1E6);
  stop-opacity: 0;
}

.rjqk0f4sw {
  stop-color: var(--svg-color--bfb0cf, #BFB0CF);
}

.rxe3dvbiw {
  stroke: var(--svg-color--959498, #959498);
  stroke-linecap: round;
  d: path("m22.19 4.725l-10.535 22.55");
}

.samx7hpzs {
  stop-color: var(--svg-color--baaec7, #BAAEC7);
  stop-opacity: 0;
}

.svn_nlb1i {
  stop-color: var(--svg-color--b8232b, #B8232B);
}

.t2wui94jw {
  stop-color: var(--svg-color--beb1cb, #BEB1CB);
}

.vbwk48lrs {
  fill: var(--svg-color--ede2f8, #EDE2F8);
  d: path("M30.041 14.327a1 1 0 0 0-.504-1.321l-3.781-1.692l-3.972 8.88a.4.4 0 0 0 .201.528l3.417 1.528a1 1 0 0 0 1.32-.505z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vpexsgv1o {
  cx: 9.559px;
  cy: 13.447px;
  r: 2.266px;
}

.w-fs0umal {
  cx: 9.559px;
  cy: 13.447px;
  r: 2.266px;
  fill: var(--svg-color--dd3240, #DD3240);
}

.wd-pmobbk {
  stop-color: var(--svg-color--d5c9e2, #D5C9E2);
}

.wstr51vhg {
  stop-color: var(--svg-color--c6c2ca, #C6C2CA);
}

.y5sqwzbee {
  stroke: var(--svg-color--959498, #959498);
  stroke-linecap: round;
  d: path("m10.727 4.725l10.535 22.55");
}

.yy3okbctu {
  stop-color: var(--svg-color--e8333e, #E8333E);
  stop-opacity: 0;
}

.z5mn73yxe {
  d: path("m24.226 17.651l-1.087-.486l-1.355 3.029a.4.4 0 0 0 .201.528l.358.16a.4.4 0 0 0 .529-.202z");
}

.zvj0vmb3h {
  stop-color: var(--svg-color--b2a3c1, #B2A3C1);
  stop-opacity: 0;
}

</style>
