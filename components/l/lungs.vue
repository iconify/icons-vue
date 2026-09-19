<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iWTjRfb)"><path fill="url(#i4gedDU)" class="qzgz-7b0c"/><path fill="url(#imXnIVd)" class="qzgz-7b0c"/></g><path fill="url(#i1fj0ed)" class="qzgz-7b0c"/><g filter="url(#iK5qvxe)"><path fill="url(#iEqhhcm)" class="uar-9vbdp"/></g><g filter="url(#iWfDzkc)"><path fill="url(#ix3ry3c)" class="b7xlidcjh"/></g><g filter="url(#iz6quTs)"><path fill="url(#iU1BdFc)" class="b893dsn3l"/></g><g filter="url(#i4ov8ve)"><path fill="url(#i42RrKd)" class="q2tjb7bqm"/></g><g filter="url(#iNbjvXb)"><path fill="url(#ihBWbqe)" class="zazfkhb6d"/></g><path fill="url(#ii44Vee)" class="nec0onb2p"/><path fill="url(#iZGQ1bd)" class="nec0onb2p"/><path class="ejm9babas"/><path fill="url(#iHIynLb)" class="udyemc-th"/><path fill="url(#iaBchmC)" class="udyemc-th"/><path fill="url(#i8MMNPc)" class="udyemc-th"/><g filter="url(#iG6EDFA)"><rect fill="url(#iULJ8pY)" class="gdsajab3b"/></g><g filter="url(#iVtQlzb)"><path fill="url(#ia43Sac)" class="b6_7w_nrb"/><path fill="url(#i6d0yxe)" class="b6_7w_nrb"/><path fill="url(#iZDiXGL)" class="b6_7w_nrb"/></g><path fill="url(#i4TygBc)" class="b6_7w_nrb"/><path fill="url(#ixj6oKd)" class="r0fj5nbno"/><path class="hq2wacc1g"/><path fill="url(#iRzB6Ib)" class="o2ee799lo"/><path fill="url(#iwOxkOe)" class="o2ee799lo"/><path fill="url(#i2maArd)" class="o2ee799lo"/><g filter="url(#ivmCYNb)"><rect fill="url(#iqo9Vpb)" class="k9ofn1m_j"/></g><g filter="url(#inAqX2k)"><path fill="url(#i6hnoMd)" class="w4cmhrbfc"/><path fill="url(#ir3VG5c)" class="w4cmhrbfc"/><path fill="url(#iW0fjkX)" class="w4cmhrbfc"/><path fill="url(#iHqXK6b)" class="w4cmhrbfc"/></g><path fill="url(#iq6EzFe)" class="w4cmhrbfc"/><g filter="url(#iwvAHQb)"><path stroke="url(#iilgfac)" class="mn-w4298j"/></g><g filter="url(#iC5sGud)"><path stroke="url(#iGUGLKe)" class="i39jzmb8u"/></g><defs><linearGradient id="i4gedDU" x1="15.956" x2="15.956" y1="4.016" y2="14.218" gradientUnits="userSpaceOnUse"><stop class="a7j_gb4tj"/><stop offset="1" class="ess1a4xiv"/></linearGradient><linearGradient id="i1fj0ed" x1="15.956" x2="15.956" y1="1.155" y2="3.701" gradientUnits="userSpaceOnUse"><stop class="cp42sjbub"/><stop offset="1" class="w3l3xcbut"/></linearGradient><linearGradient id="iEqhhcm" x1="16.253" x2="16.253" y1="2.345" y2="12.748" gradientUnits="userSpaceOnUse"><stop class="qrydfactr"/><stop offset="1" class="c4u-sgbqh"/></linearGradient><linearGradient id="iZGQ1bd" x1="8.493" x2="9.221" y1="27.255" y2="28.404" gradientUnits="userSpaceOnUse"><stop class="tv0lbubpt"/><stop offset="1" class="njw-vqbdg"/></linearGradient><linearGradient id="iHIynLb" x1=".956" x2="4.456" y1="22.438" y2="22.438" gradientUnits="userSpaceOnUse"><stop class="bb4w51apq"/><stop offset="1" class="hr-ibo5sr"/></linearGradient><linearGradient id="iaBchmC" x1="7.951" x2="7.951" y1="16.531" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="iptdakaje"/><stop offset="1" class="kf0vh9fag"/></linearGradient><linearGradient id="i8MMNPc" x1="7.951" x2="6.325" y1="28.5" y2="25.064" gradientUnits="userSpaceOnUse"><stop class="p4eq4v-tn"/><stop offset="1" class="t4jyrqbbf"/></linearGradient><linearGradient id="iULJ8pY" x1="9.674" x2="9.674" y1="29" y2="8.313" gradientUnits="userSpaceOnUse"><stop class="s-gq346xg"/><stop offset="1" class="cwqqsrb7x"/></linearGradient><linearGradient id="i6d0yxe" x1="7.951" x2="7.951" y1="17.98" y2="13.773" gradientUnits="userSpaceOnUse"><stop class="sb4r_ibln"/><stop offset="1" class="jmw-h3b3u"/></linearGradient><linearGradient id="i4TygBc" x1="7.951" x2="7.951" y1="18.745" y2="13.773" gradientUnits="userSpaceOnUse"><stop class="sb4r_ibln"/><stop offset=".588" class="jmw-h3b3u"/></linearGradient><linearGradient id="iRzB6Ib" x1="16.748" x2="20.651" y1="22.438" y2="22.438" gradientUnits="userSpaceOnUse"><stop class="bb4w51apq"/><stop offset="1" class="hr-ibo5sr"/></linearGradient><linearGradient id="iwOxkOe" x1="23.961" x2="23.961" y1="16.531" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="iptdakaje"/><stop offset="1" class="kf0vh9fag"/></linearGradient><linearGradient id="i2maArd" x1="23.961" x2="25.587" y1="28.5" y2="25.064" gradientUnits="userSpaceOnUse"><stop class="p4eq4v-tn"/><stop offset="1" class="t4jyrqbbf"/></linearGradient><linearGradient id="iqo9Vpb" x1="25.987" x2="25.987" y1="28.344" y2="15.969" gradientUnits="userSpaceOnUse"><stop class="s-gq346xg"/><stop offset=".364" class="cwqqsrb7x"/><stop offset="1" class="s-gq346xg"/></linearGradient><linearGradient id="ir3VG5c" x1="23.951" x2="23.951" y1="17.98" y2="13.773" gradientUnits="userSpaceOnUse"><stop class="sb4r_ibln"/><stop offset="1" class="jmw-h3b3u"/></linearGradient><linearGradient id="iHqXK6b" x1="17.582" x2="20.458" y1="13.463" y2="13.463" gradientUnits="userSpaceOnUse"><stop class="qsjlzq6on"/><stop offset="1" class="wnhgo8bbd"/></linearGradient><linearGradient id="iq6EzFe" x1="23.951" x2="23.951" y1="18.745" y2="13.773" gradientUnits="userSpaceOnUse"><stop class="sb4r_ibln"/><stop offset=".588" class="jmw-h3b3u"/></linearGradient><linearGradient id="iilgfac" x1="11.829" x2="17.142" y1="5.778" y2="12.994" gradientUnits="userSpaceOnUse"><stop class="zk5kb0qdg"/><stop offset="1" class="zwg_3ec_m"/></linearGradient><linearGradient id="iGUGLKe" x1="26.846" x2="32.926" y1="5.812" y2="21.177" gradientUnits="userSpaceOnUse"><stop class="zk5kb0qdg"/><stop offset="1" class="zwg_3ec_m"/></linearGradient><filter id="iWTjRfb" width="12.2" height="16.56" x="9.856" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.627451 0 0 0 0 0.34902 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="iK5qvxe" width="1.791" height="11.403" x="15.357" y="1.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5070" stdDeviation=".25"/></filter><filter id="iWfDzkc" width="3" height="1" x="14.456" y="2.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="iz6quTs" width="3" height="1" x="14.456" y="4.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="i4ov8ve" width="3" height="1" x="14.456" y="6.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.478431 0 0 0 0 0.309804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="iNbjvXb" width="3" height="1" x="14.456" y="8.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.384314 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="iG6EDFA" width="4.155" height="9.469" x="10.082" y="15.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5070" stdDeviation=".625"/></filter><filter id="iVtQlzb" width="12.14" height="13.16" x="1.956" y="4.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.545098 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="ivmCYNb" width="4.155" height="10.781" x="26.395" y="17.563" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5070" stdDeviation=".625"/></filter><filter id="inAqX2k" width="12.14" height="13.16" x="17.956" y="4.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.545098 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5070"/></filter><filter id="iwvAHQb" width="6.951" height="12.907" x="7.929" y="4.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5070" stdDeviation=".75"/></filter><filter id="iC5sGud" width="10.064" height="14.638" x="20.849" y="4.188" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5070" stdDeviation=".75"/></filter><radialGradient id="imXnIVd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1506 -5.21208 3.92046 -1.61766 18.28 15.492)" gradientUnits="userSpaceOnUse"><stop offset=".147" class="htdnsxime"/><stop offset="1" class="cuugc_bjf"/></radialGradient><radialGradient id="ix3ry3c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80269 0 0 -.72848 16.57 3.32)" gradientUnits="userSpaceOnUse"><stop class="n5tdkw7kn"/><stop offset="1" class="n10qbyq5d"/></radialGradient><radialGradient id="iU1BdFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80269 0 0 -.72848 16.57 5.33)" gradientUnits="userSpaceOnUse"><stop class="n5tdkw7kn"/><stop offset="1" class="n10qbyq5d"/></radialGradient><radialGradient id="i42RrKd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80269 0 0 -.72848 16.57 7.33)" gradientUnits="userSpaceOnUse"><stop class="wwk8lsb9e"/><stop offset="1" class="kvc577_ro"/></radialGradient><radialGradient id="ihBWbqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.68224 0 0 .67981 15.673 9.33)" gradientUnits="userSpaceOnUse"><stop class="z8mj88src"/><stop offset="1" class="qyh0aubhf"/></radialGradient><radialGradient id="ii44Vee" cx="0" cy="0" r="1" gradientTransform="matrix(1.53148 2.3519 -6.91817 4.50486 10.216 26.982)" gradientUnits="userSpaceOnUse"><stop class="jdyltpb2e"/><stop offset="1" class="d-xbhq0sv"/></radialGradient><radialGradient id="ia43Sac" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.1971 -12.2044 0 10.763 6.717)" gradientUnits="userSpaceOnUse"><stop class="j9as0xbgj"/><stop offset="1" class="wxz59xhwp"/></radialGradient><radialGradient id="iZDiXGL" cx="0" cy="0" r="1" gradientTransform="rotate(122.053 5.461 6.01)scale(7.06898 6.51477)" gradientUnits="userSpaceOnUse"><stop class="yop-3khxn"/><stop offset="1" class="o0g26ldkh"/></radialGradient><radialGradient id="ixj6oKd" cx="0" cy="0" r="1" gradientTransform="rotate(122.164 2.862 19.939)scale(3.13368 7.46021)" gradientUnits="userSpaceOnUse"><stop class="iwt_8rb1t"/><stop offset="1" class="blogr7byi"/></radialGradient><radialGradient id="i6hnoMd" cx="0" cy="0" r="1" gradientTransform="matrix(0 12.1971 -12.2044 0 21.14 6.717)" gradientUnits="userSpaceOnUse"><stop class="j9as0xbgj"/><stop offset="1" class="wxz59xhwp"/></radialGradient><radialGradient id="iW0fjkX" cx="0" cy="0" r="1" gradientTransform="matrix(2.87467 6.33909 -5.8421 2.6493 19.326 4.222)" gradientUnits="userSpaceOnUse"><stop class="yop-3khxn"/><stop offset="1" class="o0g26ldkh"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:lungs" /></template>
<style>
.a7j_gb4tj {
  stop-color: var(--svg-color--eec683, #EEC683);
}

.b6_7w_nrb {
  d: path("M13.946 8.97c0-2.21-1.79-4-4-4c-1.19 0-2.26.52-3 1.35l-2.07 2.36a11.65 11.65 0 0 0-2.92 7.71c0 .88.71 1.59 1.59 1.59h6.72c2.04 0 3.68-1.65 3.68-3.69z");
}

.b7xlidcjh {
  d: path("M16.956 3.97h-2c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h2c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.b893dsn3l {
  d: path("M16.956 5.98h-2c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h2c.28 0 .5.22.5.5c0 .27-.22.5-.5.5");
}

.bb4w51apq {
  stop-color: var(--svg-color--c7597a, #C7597A);
}

.blogr7byi {
  stop-color: var(--svg-color--a82868, #A82868);
}

.c4u-sgbqh {
  stop-color: var(--svg-color--ffe09a, #FFE09A);
  stop-opacity: 0;
}

.cp42sjbub {
  stop-color: var(--svg-color--e7c281, #E7C281);
}

.cuugc_bjf {
  stop-color: var(--svg-color--bd775b, #BD775B);
  stop-opacity: 0;
}

.cwqqsrb7x {
  stop-color: var(--svg-color--ffa9bc, #FFA9BC);
}

.d-xbhq0sv {
  stop-color: var(--svg-color--c1367c, #C1367C);
}

.ejm9babas {
  fill: var(--svg-color--f992b0, #F992B0);
  d: path("M1.956 16.39v11.3c0 1.84 2.049 2.94 3.577 1.92L11 26.18a6 6 0 0 0 2.947-5.17v-7.53z");
}

.ess1a4xiv {
  stop-color: var(--svg-color--df9f76, #DF9F76);
}

.ft5dv1b6b {
  fill: none;
}

.gdsajab3b {
  width: 1.655px;
  height: 6.969px;
  x: 11.332px;
  y: 16.594px;
  rx: 0.828px;
}

.hq2wacc1g {
  fill: var(--svg-color--f992b0, #F992B0);
  d: path("M29.956 16.39v11.3c0 1.84-2.048 2.94-3.577 1.92l-5.465-3.43a6 6 0 0 1-2.948-5.17v-7.53z");
}

.hr-ibo5sr {
  stop-color: var(--svg-color--c7597a, #C7597A);
  stop-opacity: 0;
}

.htdnsxime {
  stop-color: var(--svg-color--bd775b, #BD775B);
}

.i39jzmb8u {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m23.099 6.438l4.668 5.611l.896 4.527");
}

.iptdakaje {
  stop-color: var(--svg-color--af2f65, #AF2F65);
}

.iwt_8rb1t {
  stop-color: var(--svg-color--be4b88, #BE4B88);
}

.j9as0xbgj {
  stop-color: var(--svg-color--ff96b2, #FF96B2);
}

.jdyltpb2e {
  stop-color: var(--svg-color--db5797, #DB5797);
}

.jmw-h3b3u {
  stop-color: var(--svg-color--da4996, #DA4996);
  stop-opacity: 0;
}

.k9ofn1m_j {
  width: 1.655px;
  height: 8.281px;
  x: 27.645px;
  y: 18.813px;
  rx: 0.828px;
}

.kf0vh9fag {
  stop-color: var(--svg-color--df6d9d, #DF6D9D);
  stop-opacity: 0;
}

.kvc577_ro {
  stop-color: var(--svg-color--cf8245, #CF8245);
}

.mn-w4298j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.179 6.296c.801 0 2.45.618 2.45 2.843v5.564");
}

.n10qbyq5d {
  stop-color: var(--svg-color--db984f, #DB984F);
}

.n5tdkw7kn {
  stop-color: var(--svg-color--ffd885, #FFD885);
}

.nec0onb2p {
  d: path("M4.486 29.99h5.84c2 0 3.63-1.62 3.63-3.63v-6.12h-9.47z");
}

.njw-vqbdg {
  stop-color: var(--svg-color--b63974, #B63974);
  stop-opacity: 0;
}

.o0g26ldkh {
  stop-color: var(--svg-color--ffafb4, #FFAFB4);
  stop-opacity: 0;
}

.o2ee799lo {
  d: path("M29.956 16.39v11.3c0 1.84-2.048 2.94-3.577 1.92l-5.465-3.43a6 6 0 0 1-2.948-5.17v-7.53z");
}

.p4eq4v-tn {
  stop-color: var(--svg-color--c8419e, #C8419E);
}

.q2tjb7bqm {
  d: path("M16.956 7.98h-2c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h2c.28 0 .5.22.5.5c0 .27-.22.5-.5.5");
}

.qrydfactr {
  stop-color: var(--svg-color--ffe09a, #FFE09A);
}

.qsjlzq6on {
  stop-color: var(--svg-color--df6886, #DF6886);
}

.qyh0aubhf {
  stop-color: var(--svg-color--d18045, #D18045);
}

.qzgz-7b0c {
  d: path("m22.056 17.14l-4.95-4.95q-.15-.15-.15-.36V2.31c0-.17-.14-.31-.31-.31h-1.38c-.17 0-.31.14-.31.31v9.52c0 .13-.05.26-.15.35l-4.95 4.96l1.41 1.42l4.51-4.51c.1-.1.26-.1.35 0l4.51 4.51z");
}

.r0fj5nbno {
  d: path("M27.426 29.99h-5.84c-2 0-3.63-1.62-3.63-3.63v-6.12h9.46v9.75z");
}

.s-gq346xg {
  stop-color: var(--svg-color--ffa9bc, #FFA9BC);
  stop-opacity: 0;
}

.sb4r_ibln {
  stop-color: var(--svg-color--da4996, #DA4996);
}

.t4jyrqbbf {
  stop-color: var(--svg-color--c8419e, #C8419E);
  stop-opacity: 0;
}

.tv0lbubpt {
  stop-color: var(--svg-color--b63974, #B63974);
}

.uar-9vbdp {
  d: path("M15.857 2.345h.791v10.403h-.791z");
}

.udyemc-th {
  d: path("M1.956 16.39v11.3c0 1.84 2.049 2.94 3.577 1.92L11 26.18a6 6 0 0 0 2.947-5.17v-7.53z");
}

.w3l3xcbut {
  stop-color: var(--svg-color--e7c281, #E7C281);
  stop-opacity: 0;
}

.w4cmhrbfc {
  d: path("M17.956 8.97c0-2.21 1.79-4 4-4c1.19 0 2.26.52 3 1.35l2.07 2.36c1.88 2.13 2.92 4.87 2.92 7.71c0 .88-.71 1.59-1.59 1.59h-6.72c-2.04 0-3.68-1.65-3.68-3.69z");
}

.wnhgo8bbd {
  stop-color: var(--svg-color--df6886, #DF6886);
  stop-opacity: 0;
}

.wwk8lsb9e {
  stop-color: var(--svg-color--fac376, #FAC376);
}

.wxz59xhwp {
  stop-color: var(--svg-color--f57db1, #F57DB1);
}

.yop-3khxn {
  stop-color: var(--svg-color--ffafb4, #FFAFB4);
}

.z8mj88src {
  stop-color: var(--svg-color--e7a866, #E7A866);
}

.zazfkhb6d {
  d: path("M16.956 9.98h-2c-.28 0-.5-.22-.5-.5s.22-.5.5-.5h2c.28 0 .5.22.5.5s-.22.5-.5.5");
}

.zk5kb0qdg {
  stop-color: var(--svg-color--ffbbc6, #FFBBC6);
}

.zwg_3ec_m {
  stop-color: var(--svg-color--ffbbc6, #FFBBC6);
  stop-opacity: 0;
}

</style>
