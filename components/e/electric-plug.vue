<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVQGoPe)"><path fill="url(#ix8tTGc)" class="sh43pcuev"/></g><g filter="url(#iBLkP1c)"><path fill="url(#irxuYUJ)" class="uwzqrwbrg"/></g><g filter="url(#iWMOTac)"><path fill="url(#iL7IOwc)" class="cxuyihbwe"/></g><g filter="url(#iK2jYlm)"><path fill="url(#i8pO4ed)" class="m65f2vi6w"/></g><path fill="url(#iCyuvnd)" class="muxqrsb8w"/><path fill="url(#itxqVLd)" class="muxqrsb8w"/><path fill="url(#i6RCsgd)" class="muxqrsb8w"/><path fill="url(#ilwjoLb)" class="co-gb91um"/><path fill="url(#iq7Zshe)" class="co-gb91um"/><path fill="url(#iiJ8Tkc)" class="co-gb91um"/><path fill="url(#i1PZrId)" class="co-gb91um"/><path fill="url(#idveUpe)" class="co-gb91um"/><path fill="url(#iy4r5nb)" class="h68ds46no"/><path fill="url(#i2UCXLh)" class="h68ds46no"/><path fill="url(#i18zVre)" class="h68ds46no"/><g filter="url(#iJSV23b)"><path class="jwxn4nbog"/></g><path fill="url(#iYZ268c)" class="tl4tx9bsq"/><path fill="url(#ijh0nuP)" class="tl4tx9bsq"/><path fill="url(#ibhOfOb)" class="tl4tx9bsq"/><g filter="url(#iR3Bc6b)"><path fill="url(#iSC8lGd)" class="tqhl37_-m"/></g><g filter="url(#iGcqDzd)"><path fill="url(#ixqZzec)" class="n1n02e0rb"/></g><g filter="url(#i9LDfSd)"><rect fill="url(#iUHYL9I)" class="tfl6ds77h"/><rect fill="url(#iMw1nPc)" class="tfl6ds77h"/></g><g filter="url(#iGYTV7n)"><rect fill="url(#iiLkj6d)" class="l-aycubwu"/><rect fill="url(#ihtVFmc)" class="l-aycubwu"/></g><defs><linearGradient id="ix8tTGc" x1="13.542" x2="13.542" y1="1.969" y2="8.078" gradientUnits="userSpaceOnUse"><stop offset=".074" class="nzkgfgbaf"/><stop offset="1" class="g2p8ll1id"/></linearGradient><linearGradient id="irxuYUJ" x1="13.917" x2="13.917" y1="2.422" y2="7.969" gradientUnits="userSpaceOnUse"><stop class="iicu47b8q"/><stop offset="1" class="lq9rpfkgj"/></linearGradient><linearGradient id="iL7IOwc" x1="18.511" x2="18.511" y1="1.969" y2="8.078" gradientUnits="userSpaceOnUse"><stop offset=".074" class="nzkgfgbaf"/><stop offset="1" class="g2p8ll1id"/></linearGradient><linearGradient id="i8pO4ed" x1="18.886" x2="18.886" y1="2.422" y2="7.969" gradientUnits="userSpaceOnUse"><stop class="iicu47b8q"/><stop offset="1" class="lq9rpfkgj"/></linearGradient><linearGradient id="iCyuvnd" x1="15.226" x2="17.319" y1="28.578" y2="28.578" gradientUnits="userSpaceOnUse"><stop offset=".194" class="bjaf4cc9l"/><stop offset=".701" class="zaf_gsx4r"/></linearGradient><linearGradient id="itxqVLd" x1="17.585" x2="17.241" y1="29.328" y2="29.328" gradientUnits="userSpaceOnUse"><stop offset=".352" class="hyqszeb-o"/><stop offset="1" class="lgsw6t4gw"/></linearGradient><linearGradient id="i6RCsgd" x1="14.532" x2="15.007" y1="29.328" y2="29.328" gradientUnits="userSpaceOnUse"><stop class="njc4wk1ya"/><stop offset="1" class="ij_z_88hc"/></linearGradient><linearGradient id="ilwjoLb" x1="17.57" x2="15.413" y1="21.984" y2="21.984" gradientUnits="userSpaceOnUse"><stop offset=".232" class="v_hm_vb5w"/><stop offset="1" class="q7kbm8_yc"/></linearGradient><linearGradient id="iq7Zshe" x1="13.351" x2="14.413" y1="20.859" y2="20.859" gradientUnits="userSpaceOnUse"><stop class="fyse9kb_r"/><stop offset="1" class="t3ivanboa"/></linearGradient><linearGradient id="iiJ8Tkc" x1="16.882" x2="16.882" y1="22.922" y2="21.766" gradientUnits="userSpaceOnUse"><stop offset=".311" class="jy6v8xbqz"/><stop offset="1" class="x4y2msbuc"/></linearGradient><linearGradient id="i2UCXLh" x1="10.226" x2="13.069" y1="13.242" y2="13.242" gradientUnits="userSpaceOnUse"><stop class="hyqszeb-o"/><stop offset="1" class="lgsw6t4gw"/></linearGradient><linearGradient id="iYZ268c" x1="16.026" x2="16.026" y1="6.984" y2="9.992" gradientUnits="userSpaceOnUse"><stop class="xj-0gv5-a"/><stop offset="1" class="wsmsa5b3s"/></linearGradient><linearGradient id="iSC8lGd" x1="16.21" x2="18.07" y1="11.473" y2="11.473" gradientUnits="userSpaceOnUse"><stop class="kj8k4zygc"/><stop offset=".901" class="mx0xr3bak"/></linearGradient><linearGradient id="ixqZzec" x1="16.21" x2="18.07" y1="13.449" y2="13.449" gradientUnits="userSpaceOnUse"><stop class="kj8k4zygc"/><stop offset=".901" class="mx0xr3bak"/></linearGradient><linearGradient id="iUHYL9I" x1="17.64" x2="15.051" y1="11.748" y2="11.748" gradientUnits="userSpaceOnUse"><stop class="fjc1pvb2l"/><stop offset="1" class="wk10h8bmp"/></linearGradient><linearGradient id="iMw1nPc" x1="14.475" x2="14.944" y1="11.673" y2="11.673" gradientUnits="userSpaceOnUse"><stop offset=".193" class="fjc1pvb2l"/><stop offset="1" class="wk10h8bmp"/></linearGradient><linearGradient id="iiLkj6d" x1="17.626" x2="15.037" y1="13.732" y2="13.732" gradientUnits="userSpaceOnUse"><stop class="fjc1pvb2l"/><stop offset="1" class="wk10h8bmp"/></linearGradient><linearGradient id="ihtVFmc" x1="14.461" x2="14.93" y1="13.657" y2="13.657" gradientUnits="userSpaceOnUse"><stop offset=".193" class="fjc1pvb2l"/><stop offset="1" class="wk10h8bmp"/></linearGradient><filter id="iVQGoPe" width="2.069" height="8.202" x="12.558" y="1.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.745098 0 0 0 0 0.498039 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19384"/></filter><filter id="iBLkP1c" width="1.363" height="6.347" x="13.236" y="2.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19384" stdDeviation=".2"/></filter><filter id="iWMOTac" width="2.069" height="8.202" x="17.526" y="1.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.470588 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19384"/></filter><filter id="iK2jYlm" width="1.363" height="6.347" x="18.204" y="2.022" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19384" stdDeviation=".2"/></filter><filter id="iJSV23b" width="7.493" height="10.016" x="14.976" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19384" stdDeviation="1"/></filter><filter id="iR3Bc6b" width="3.844" height="1.242" x="14.104" y="10.977" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.305882 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19384"/></filter><filter id="iGcqDzd" width="3.844" height="1.242" x="14.104" y="12.953" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.305882 0 0 0 0 0.768627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_19384"/></filter><filter id="i9LDfSd" width="3.752" height=".826" x="14.138" y="11.172" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19384" stdDeviation=".125"/></filter><filter id="iGYTV7n" width="3.752" height=".826" x="14.124" y="13.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_19384" stdDeviation=".125"/></filter><radialGradient id="i1PZrId" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.29688 2.60562 0 16.026 22.922)" gradientUnits="userSpaceOnUse"><stop class="bkrqwcbys"/><stop offset="1" class="k40djjpvm"/></radialGradient><radialGradient id="idveUpe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.35938 -2.61327 0 16.026 17.64)" gradientUnits="userSpaceOnUse"><stop class="d8xjeqkqk"/><stop offset="1" class="iywcwac1l"/></radialGradient><radialGradient id="iy4r5nb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.03125 9.84375 0 16.195 18.422)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="j0-f-kbnq"/><stop offset="1" class="fxka3kbun"/></radialGradient><radialGradient id="i18zVre" cx="0" cy="0" r="1" gradientTransform="matrix(0 .84375 -6.92563 0 16.026 9.578)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="laptv3bsy"/><stop offset="1" class="ykgerkblv"/></radialGradient><radialGradient id="ijh0nuP" cx="0" cy="0" r="1" gradientTransform="matrix(3.9378 0 0 2.46875 9.538 8.234)" gradientUnits="userSpaceOnUse"><stop class="m9-lw9bzv"/><stop offset="1" class="mjic42bbr"/></radialGradient><radialGradient id="ibhOfOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.3125 -5.66263 0 19.413 8.078)" gradientUnits="userSpaceOnUse"><stop class="z6pnz2e2q"/><stop offset="1" class="mx1fzvb-a"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:electric-plug" /></template>
<style>
.bjaf4cc9l {
  stop-color: var(--svg-color--38333e, #38333E);
}

.bkrqwcbys {
  stop-color: var(--svg-color--2a1e35, #2A1E35);
}

.co-gb91um {
  d: path("M13.534 16h4.985v5.922a1 1 0 0 1-1 1h-2.985a1 1 0 0 1-1-1z");
}

.cxuyihbwe {
  d: path("M17.526 2.953a.984.984 0 1 1 1.97 0v6.133a.984.984 0 1 1-1.97 0z");
}

.d8xjeqkqk {
  stop-color: var(--svg-color--2b2234, #2B2234);
}

.fjc1pvb2l {
  stop-color: var(--svg-color--8f6dd2, #8F6DD2);
}

.ft5dv1b6b {
  fill: none;
}

.fxka3kbun {
  stop-color: var(--svg-color--393240, #393240);
}

.fyse9kb_r {
  stop-color: var(--svg-color--504f52, #504F52);
}

.g2p8ll1id {
  stop-color: var(--svg-color--c1834b, #C1834B);
}

.h68ds46no {
  d: path("M10.558 7.828h10.937v5.36a5.469 5.469 0 1 1-10.937 0z");
}

.hyqszeb-o {
  stop-color: var(--svg-color--4e4b51, #4E4B51);
}

.iicu47b8q {
  stop-color: var(--svg-color--f3c39a, #F3C39A);
}

.ij_z_88hc {
  stop-color: var(--svg-color--4f4d51, #4F4D51);
  stop-opacity: 0;
}

.iywcwac1l {
  stop-color: var(--svg-color--2b2234, #2B2234);
  stop-opacity: 0;
}

.j0-f-kbnq {
  stop-color: var(--svg-color--352346, #352346);
}

.jwxn4nbog {
  fill: var(--svg-color--544e5a, #544E5A);
  d: path("M16.976 9.016h3.493v4.269a1.746 1.746 0 0 1-3.493 0z");
}

.jy6v8xbqz {
  stop-color: var(--svg-color--392948, #392948);
}

.k40djjpvm {
  stop-color: var(--svg-color--2a1e35, #2A1E35);
  stop-opacity: 0;
}

.kj8k4zygc {
  stop-color: var(--svg-color--7d53c7, #7D53C7);
}

.l-aycubwu {
  width: 3.252px;
  height: 0.326px;
  x: 14.374px;
  y: 13.406px;
  rx: 0.163px;
}

.laptv3bsy {
  stop-color: var(--svg-color--291e34, #291E34);
}

.lgsw6t4gw {
  stop-color: var(--svg-color--4e4b51, #4E4B51);
  stop-opacity: 0;
}

.lq9rpfkgj {
  stop-color: var(--svg-color--f3c39a, #F3C39A);
  stop-opacity: 0;
}

.m65f2vi6w {
  d: path("M18.605 2.703a.281.281 0 1 1 .562 0v4.985a.281.281 0 1 1-.562 0z");
}

.m9-lw9bzv {
  stop-color: var(--svg-color--524f54, #524F54);
}

.mjic42bbr {
  stop-color: var(--svg-color--524f54, #524F54);
  stop-opacity: 0;
}

.muxqrsb8w {
  d: path("M14.532 22.289h2.988v7.641h-2.988z");
}

.mx0xr3bak {
  stop-color: var(--svg-color--734cbd, #734CBD);
}

.mx1fzvb-a {
  stop-color: var(--svg-color--635d69, #635D69);
  stop-opacity: 0;
}

.n1n02e0rb {
  d: path("M14.105 13.449c0-.274.222-.496.496-.496h2.851a.496.496 0 1 1 0 .992h-2.851a.496.496 0 0 1-.497-.496");
}

.njc4wk1ya {
  stop-color: var(--svg-color--4f4d51, #4F4D51);
}

.nzkgfgbaf {
  stop-color: var(--svg-color--dba572, #DBA572);
}

.q7kbm8_yc {
  stop-color: var(--svg-color--36303d, #36303D);
}

.sh43pcuev {
  d: path("M12.558 2.953a.984.984 0 1 1 1.968 0v6.133a.984.984 0 0 1-1.968 0z");
}

.t3ivanboa {
  stop-color: var(--svg-color--504f52, #504F52);
  stop-opacity: 0;
}

.tfl6ds77h {
  width: 3.252px;
  height: 0.326px;
  x: 14.388px;
  y: 11.422px;
  rx: 0.163px;
}

.tl4tx9bsq {
  d: path("M9.538 8.488c0-.83.673-1.504 1.504-1.504h9.969a1.504 1.504 0 1 1 0 3.008h-9.97c-.83 0-1.503-.673-1.503-1.504");
}

.tqhl37_-m {
  d: path("M14.105 11.473c0-.274.222-.496.496-.496h2.851a.496.496 0 1 1 0 .992h-2.851a.496.496 0 0 1-.497-.496");
}

.uwzqrwbrg {
  d: path("M13.636 2.703a.281.281 0 0 1 .562 0v4.985a.281.281 0 1 1-.562 0z");
}

.v_hm_vb5w {
  stop-color: var(--svg-color--534e59, #534E59);
}

.wk10h8bmp {
  stop-color: var(--svg-color--8f6dd2, #8F6DD2);
  stop-opacity: 0;
}

.wsmsa5b3s {
  stop-color: var(--svg-color--382548, #382548);
}

.x4y2msbuc {
  stop-color: var(--svg-color--392948, #392948);
  stop-opacity: 0;
}

.xj-0gv5-a {
  stop-color: var(--svg-color--3d3642, #3D3642);
}

.ykgerkblv {
  stop-color: var(--svg-color--291e34, #291E34);
  stop-opacity: 0;
}

.z6pnz2e2q {
  stop-color: var(--svg-color--635d69, #635D69);
}

.zaf_gsx4r {
  stop-color: var(--svg-color--534f58, #534F58);
}

</style>
