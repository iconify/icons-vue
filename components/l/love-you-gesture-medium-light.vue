<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iXRKhEe)"><path class="kulr6t2wi"/><path fill="url(#iMsOODd)" class="t9w5z_byo"/><path fill="url(#iTuHuyl)" class="t9w5z_byo"/><path fill="url(#icMblDb)" class="t9w5z_byo"/><path fill="url(#ioWP0Jo)" class="t9w5z_byo"/></g><path fill="url(#isp5qOc)" class="t9w5z_byo"/><path fill="url(#iEtJtCe)" class="t9w5z_byo"/><g filter="url(#ieJRKbe)"><rect class="uucso-bnw"/></g><g filter="url(#ii4eOdc)"><rect class="v56pye80b"/></g><path class="frv4ifbyv"/><path fill="url(#i5TvdNc)" class="sa4gncu6p"/><path fill="url(#igNZNGb)" class="sa4gncu6p"/><path fill="url(#irx9iGG)" class="sa4gncu6p"/><path fill="url(#i1yR5Ce)" class="sa4gncu6p"/><path fill="url(#i32gbJe)" class="r49-4542o"/><path fill="url(#imi2lUc)" class="r49-4542o"/><path fill="url(#iAMUX2b)" class="r49-4542o"/><path fill="url(#i8hjXyT)" class="r49-4542o"/><g filter="url(#idq7Bvb)"><rect fill="url(#iD83cze)" class="imd735f1f"/><rect fill="url(#i0Wh26c)" class="imd735f1f"/><rect fill="url(#iaZ94ge)" class="imd735f1f"/></g><g filter="url(#iMfMeoe)"><rect fill="url(#iDqJBZd)" class="tb7m8k9zy"/></g><g filter="url(#ifPSCqd)"><rect fill="url(#iw1EGse)" class="iov6ep38u"/></g><g filter="url(#iiTeOwe)"><rect class="fqu_tnj6p"/></g><g filter="url(#iKAxnve)"><rect fill="url(#iRJd4Rd)" class="r0-rlacem"/></g><g filter="url(#iAQsrpc)"><rect class="e0ihf-1br"/></g><defs><radialGradient id="iMsOODd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.14246 2.5592 -1.38196 -3.8569 10.827 11.301)" gradientUnits="userSpaceOnUse"><stop class="b4n4a5yod"/><stop offset="1" class="gn91b6bkg"/></radialGradient><radialGradient id="iTuHuyl" cx="0" cy="0" r="1" gradientTransform="matrix(-8.93158 3.02526 -4.1051 -12.11964 23.622 18.295)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="c-t584bua"/><stop offset="1" class="oexw0abgw"/></radialGradient><radialGradient id="icMblDb" cx="0" cy="0" r="1" gradientTransform="translate(7.75 7.465)scale(1.81597)" gradientUnits="userSpaceOnUse"><stop class="xgeh8nqil"/><stop offset="1" class="tg7cjccub"/></radialGradient><radialGradient id="ioWP0Jo" cx="0" cy="0" r="1" gradientTransform="matrix(1 -7.62019 14.88379 1.9532 11.378 29.893)" gradientUnits="userSpaceOnUse"><stop class="dpy7ucboa"/><stop offset="1" class="g09328pji"/><stop offset="1" class="p0e31fb5s"/></radialGradient><radialGradient id="i5TvdNc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.82462 -2.27134 3.5664 -12.28604 30.465 17.835)" gradientUnits="userSpaceOnUse"><stop offset=".676" class="aljfjo_5c"/><stop offset=".975" class="b0fngbclm"/></radialGradient><radialGradient id="igNZNGb" cx="0" cy="0" r="1" gradientTransform="rotate(135.167 9.315 15.368)scale(8.73491 2.30407)" gradientUnits="userSpaceOnUse"><stop class="r83xxrtvq"/><stop offset="1" class="xop6hab-h"/></radialGradient><radialGradient id="irx9iGG" cx="0" cy="0" r="1" gradientTransform="rotate(144.638 12.384 11.63)scale(2.76123 1.79671)" gradientUnits="userSpaceOnUse"><stop class="zc2rh-bte"/><stop offset="1" class="m4g3qib9j"/></radialGradient><radialGradient id="i1yR5Ce" cx="0" cy="0" r="1" gradientTransform="rotate(45.707 -3.902 35.75)scale(1.1207 2.36718)" gradientUnits="userSpaceOnUse"><stop class="flp2-dbgc"/><stop offset="1" class="ysibjqn3l"/></radialGradient><radialGradient id="iAMUX2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.6875 0 0 1.53125 21.5 3.773)" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></radialGradient><radialGradient id="i8hjXyT" cx="0" cy="0" r="1" gradientTransform="matrix(1.25183 0 0 3.53051 17.087 9.88)" gradientUnits="userSpaceOnUse"><stop class="ow173uiyy"/><stop offset="1" class="rpz272r0m"/></radialGradient><radialGradient id="iaZ94ge" cx="0" cy="0" r="1" gradientTransform="rotate(149.179 5.232 6.993)scale(1.07751 2.24971)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="br24ssbkd"/><stop offset="1" class="qn95aebcu"/></radialGradient><linearGradient id="isp5qOc" x1="4.375" x2="7.688" y1="19.773" y2="19.836" gradientUnits="userSpaceOnUse"><stop class="vtd83yhro"/><stop offset="1" class="fjn36si1c"/></linearGradient><linearGradient id="iEtJtCe" x1="3.684" x2="4.5" y1="18.516" y2="18.516" gradientUnits="userSpaceOnUse"><stop class="z999isbkq"/><stop offset="1" class="ou1m6wbsm"/></linearGradient><linearGradient id="i32gbJe" x1="17.559" x2="20.396" y1="8.355" y2="8.355" gradientUnits="userSpaceOnUse"><stop class="zm6xbtjwf"/><stop offset="1" class="ct6f_4yoz"/></linearGradient><linearGradient id="imi2lUc" x1="19.337" x2="19.337" y1="12.748" y2="10.371" gradientUnits="userSpaceOnUse"><stop class="idfn3dfoy"/><stop offset="1" class="uynucabmz"/></linearGradient><linearGradient id="iD83cze" x1="9.454" x2="12.282" y1="11.502" y2="11.616" gradientUnits="userSpaceOnUse"><stop class="p8o-ahxbh"/><stop offset="1" class="nhconhojc"/></linearGradient><linearGradient id="i0Wh26c" x1="12.746" x2="12.035" y1="12.965" y2="12.965" gradientUnits="userSpaceOnUse"><stop class="fz6u-zlhf"/><stop offset="1" class="ot6jq-byw"/></linearGradient><linearGradient id="iDqJBZd" x1="13.55" x2="17.776" y1="10.576" y2="10.576" gradientUnits="userSpaceOnUse"><stop class="f28zkabar"/><stop offset="1" class="e8j22abae"/></linearGradient><linearGradient id="iw1EGse" x1="20.65" x2="20.65" y1="3.657" y2="14.102" gradientUnits="userSpaceOnUse"><stop class="zc2rh-bte"/><stop offset="1" class="b4gpdrxyu"/><stop offset="1" class="m4g3qib9j"/></linearGradient><linearGradient id="iRJd4Rd" x1="6.961" x2="6.961" y1="8.046" y2="19.378" gradientUnits="userSpaceOnUse"><stop class="gkutxmb2p"/><stop offset="1" class="ocfx7-bfg"/></linearGradient><filter id="iXRKhEe" width="26.567" height="28.515" x="3.684" y="1.378" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.439216 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2368"/></filter><filter id="ieJRKbe" width="6.696" height="8.966" x="10.804" y="9.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2368" stdDeviation=".75"/></filter><filter id="ii4eOdc" width="8.409" height="11.255" x="5.696" y="8.195" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2368" stdDeviation="1"/></filter><filter id="idq7Bvb" width="5.922" height="9.222" x="8.135" y="8.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.478431 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2368"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.588235 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2368" result="effect2_innerShadow_20020_2368"/></filter><filter id="iMfMeoe" width="5.828" height="11.084" x="12.698" y="6.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.737255 0 0 0 0 0.470588 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2368"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".6"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.796078 0 0 0 0 0.54902 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2368" result="effect2_innerShadow_20020_2368"/></filter><filter id="ifPSCqd" width="4.636" height="13.444" x="18.332" y="2.157" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2368" stdDeviation=".75"/></filter><filter id="iiTeOwe" width="5.468" height="10.264" x="13.519" y="7.052" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2368" stdDeviation="1"/></filter><filter id="iKAxnve" width="4.468" height="11.935" x="4.727" y="5.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2368" stdDeviation=".75"/></filter><filter id="iAQsrpc" width="4.027" height="7.274" x="9.221" y="8.985" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2368" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:love-you-gesture-medium-light" /></template>
<style>
.aljfjo_5c {
  stop-color: var(--svg-color--f8c1a1, #F8C1A1);
  stop-opacity: 0;
}

.b0fngbclm {
  stop-color: var(--svg-color--ffc9a6, #FFC9A6);
}

.b4gpdrxyu {
  stop-color: var(--svg-color--cca48d, #CCA48D);
  stop-opacity: 0;
}

.b4n4a5yod {
  stop-color: var(--svg-color--b1705d, #B1705D);
}

.br24ssbkd {
  stop-color: var(--svg-color--a76f46, #A76F46);
}

.c-t584bua {
  stop-color: var(--svg-color--fec8a5, #FEC8A5);
}

.ct6f_4yoz {
  stop-color: var(--svg-color--cf9067, #CF9067);
  stop-opacity: 0;
}

.dpy7ucboa {
  stop-color: var(--svg-color--da9c95, #DA9C95);
}

.e0ihf-1br {
  width: 1.027px;
  height: 4.274px;
  x: 10.721px;
  y: 10.485px;
  fill: var(--svg-color--f1c0a3, #F1C0A3);
  rx: 0.513px;
}

.e8j22abae {
  stop-color: var(--svg-color--f9c79b, #F9C79B);
}

.f28zkabar {
  stop-color: var(--svg-color--ce9b79, #CE9B79);
}

.fjn36si1c {
  stop-color: var(--svg-color--ce977b, #CE977B);
  stop-opacity: 0;
}

.flp2-dbgc {
  stop-color: var(--svg-color--ca9470, #CA9470);
}

.fqu_tnj6p {
  width: 1.468px;
  height: 6.264px;
  x: 15.519px;
  y: 9.052px;
  fill: var(--svg-color--ffd0a7, #FFD0A7);
  rx: 0.734px;
}

.frv4ifbyv {
  fill: var(--svg-color--ebb792, #EBB792);
  d: path("M25.698 12.919c1.234-.641 2.598-.16 3.297.648c.945 1.094.744 2.918-.313 3.79c-.278.229-.617.49-.988.775c-1.035.797-2.315 1.784-3.207 2.802c-.793.845-1.248 1.513-1.583 2.115c-1.492-3.69-1.037-6.778-.367-8.437c.165.315.583.03.583.03c.37-.347 1.343-1.083 2.578-1.723");
}

.ft5dv1b6b {
  fill: none;
}

.fz6u-zlhf {
  stop-color: var(--svg-color--c1865c, #C1865C);
}

.g09328pji {
  stop-color: var(--svg-color--ae797e, #AE797E);
  stop-opacity: 0;
}

.gkutxmb2p {
  stop-color: var(--svg-color--f9c79f, #F9C79F);
}

.gn91b6bkg {
  stop-color: var(--svg-color--b1705d, #B1705D);
  stop-opacity: 0;
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.idfn3dfoy {
  stop-color: var(--svg-color--e9b498, #E9B498);
}

.imd735f1f {
  width: 5.172px;
  height: 8.172px;
  x: 8.135px;
  y: 8.879px;
  rx: 2.539px;
}

.iov6ep38u {
  width: 1.636px;
  height: 10.444px;
  x: 19.832px;
  y: 3.657px;
  rx: 0.818px;
}

.kulr6t2wi {
  fill: var(--svg-color--dfa78f, #DFA78F);
  d: path("M28.995 13.567c-.699-.809-2.063-1.29-3.297-.649c-1.235.641-2.208 1.377-2.578 1.723c0 0-.649.444-.649-.384v-9.26c0-1.672-1.125-2.97-2.625-2.97c-1.406 0-2.625 1.126-2.625 2.97l-.038 7.506H8.909V8.528c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.102 4.328 10.26 9.653 10.26c2.709 0 5.41-1.221 7.189-3.093c2.258-2.375 1.563-3.312 3.961-5.867c1.21-1.383 3.139-2.707 4.195-3.578s1.258-2.695.313-3.789");
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.m4g3qib9j {
  stop-color: var(--svg-color--ffcfaa, #FFCFAA);
  stop-opacity: 0;
}

.nhconhojc {
  stop-color: var(--svg-color--dcab88, #DCAB88);
}

.ocfx7-bfg {
  stop-color: var(--svg-color--f9c79f, #F9C79F);
  stop-opacity: 0;
}

.oexw0abgw {
  stop-color: var(--svg-color--fec8a5, #FEC8A5);
  stop-opacity: 0;
}

.ot6jq-byw {
  stop-color: var(--svg-color--c1865c, #C1865C);
  stop-opacity: 0;
}

.ou1m6wbsm {
  stop-color: var(--svg-color--e0a587, #E0A587);
  stop-opacity: 0;
}

.ow173uiyy {
  stop-color: var(--svg-color--c8875d, #C8875D);
}

.p0e31fb5s {
  stop-color: var(--svg-color--da9c95, #DA9C95);
  stop-opacity: 0;
}

.p8o-ahxbh {
  stop-color: var(--svg-color--cf9b7a, #CF9B7A);
}

.qn95aebcu {
  stop-color: var(--svg-color--a76f46, #A76F46);
  stop-opacity: 0;
}

.r0-rlacem {
  width: 1.468px;
  height: 8.935px;
  x: 6.227px;
  y: 7.065px;
  rx: 0.734px;
}

.r49-4542o {
  d: path("M22.476 12.5h-5.288l.038-7.503c0-1.844 1.219-2.97 2.625-2.97c1.5 0 2.625 1.298 2.625 2.97z");
}

.r83xxrtvq {
  stop-color: var(--svg-color--c8928c, #C8928C);
}

.rpz272r0m {
  stop-color: var(--svg-color--c8875d, #C8875D);
  stop-opacity: 0;
}

.sa4gncu6p {
  d: path("M25.698 12.919c1.234-.641 2.598-.16 3.297.648c.945 1.094.744 2.918-.313 3.79c-.278.229-.617.49-.988.775c-1.035.797-2.315 1.784-3.207 2.802c-.793.845-1.248 1.513-1.583 2.115c-1.492-3.69-1.037-6.778-.367-8.437c.165.315.583.03.583.03c.37-.347 1.343-1.083 2.578-1.723");
}

.t9w5z_byo {
  d: path("M28.995 13.567c-.699-.809-2.063-1.29-3.297-.649c-1.235.641-2.208 1.377-2.578 1.723c0 0-.649.444-.649-.384v-9.26c0-1.672-1.125-2.97-2.625-2.97c-1.406 0-2.625 1.126-2.625 2.97l-.038 7.506H8.909V8.528c0-1.656-1.157-2.88-2.594-2.88c-1.438 0-2.614 1.408-2.614 2.767c0 1.36-.017 11.219-.017 11.219c0 7.102 4.328 10.26 9.653 10.26c2.709 0 5.41-1.221 7.189-3.093c2.258-2.375 1.563-3.312 3.961-5.867c1.21-1.383 3.139-2.707 4.195-3.578s1.258-2.695.313-3.789");
}

.tb7m8k9zy {
  width: 5.078px;
  height: 9.734px;
  x: 12.698px;
  y: 7.317px;
  rx: 2.539px;
}

.tg7cjccub {
  stop-color: var(--svg-color--fccaa3, #FCCAA3);
  stop-opacity: 0;
}

.uucso-bnw {
  width: 3.696px;
  height: 5.966px;
  x: 12.304px;
  y: 11.484px;
  fill: var(--svg-color--8a4940, #8A4940);
  rx: 1.848px;
}

.uynucabmz {
  stop-color: var(--svg-color--e9b498, #E9B498);
  stop-opacity: 0;
}

.v56pye80b {
  width: 4.409px;
  height: 7.256px;
  x: 7.696px;
  y: 10.195px;
  fill: var(--svg-color--8a4940, #8A4940);
  rx: 2.204px;
}

.vtd83yhro {
  stop-color: var(--svg-color--ce977b, #CE977B);
}

.xgeh8nqil {
  stop-color: var(--svg-color--fccaa3, #FCCAA3);
}

.xop6hab-h {
  stop-color: var(--svg-color--c8928c, #C8928C);
  stop-opacity: 0;
}

.ysibjqn3l {
  stop-color: var(--svg-color--ca9470, #CA9470);
  stop-opacity: 0;
}

.z999isbkq {
  stop-color: var(--svg-color--e0a587, #E0A587);
}

.zc2rh-bte {
  stop-color: var(--svg-color--ffcfaa, #FFCFAA);
}

.zm6xbtjwf {
  stop-color: var(--svg-color--cf9067, #CF9067);
}

</style>
