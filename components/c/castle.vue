<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i9zIRdd)"><path class="ax-coj_na"/><path fill="url(#iFqsQne)" class="esch9bkuf"/><path fill="url(#iajBUlb)" class="esch9bkuf"/></g><g filter="url(#iZBC7cb)"><path fill="url(#iZlLq9V)" class="p4o9db_oe"/></g><g filter="url(#iHsmzZc)"><path fill="url(#iTSTsSd)" class="uob74k9bp"/><path fill="url(#imQgNee)" class="uob74k9bp"/></g><path fill="url(#iV0yhvc)" class="ibeh_mbmn"/><g filter="url(#io0XKJd)"><path class="n0rnws0ga"/><path fill="url(#iSBZYcd)" class="cusot8b3f"/></g><g filter="url(#igOOZde)"><path class="yx8451qay"/><path fill="url(#i1iPuNd)" class="hj6u20cdv"/><path fill="url(#i4udJLe)" class="hj6u20cdv"/><path fill="url(#in05gud)" class="hj6u20cdv"/><path fill="url(#iaiT2ew)" class="hj6u20cdv"/></g><g filter="url(#iU6LLXd)"><path class="ivp13gbyw"/></g><path fill="url(#iEC8yKc)" class="clrkfzw9s"/><path fill="url(#iopxbho)" class="clrkfzw9s"/><path fill="url(#iB3atVc)" class="onyhz3txt"/><path fill="url(#iYJjx7d)" class="onyhz3txt"/><g filter="url(#iIujPnd)"><path fill="url(#irCNGcd)" class="r4w8e6bye"/></g><g filter="url(#iDWFyWI)"><path class="ib_uut75k"/></g><path fill="url(#ifaJare)" class="hqiqkghpo"/><g filter="url(#iTlPbkJ)"><path fill="url(#i1t9yJe)" class="to7pjn83v"/></g><g filter="url(#ig4r7NS)"><path fill="url(#i99orwi)" class="mr2xw04hq"/></g><defs><linearGradient id="iFqsQne" x1="18.44" x2="15.476" y1="7.451" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="yuovncbrz"/><stop offset="1" class="gzgfd1blq"/></linearGradient><linearGradient id="iajBUlb" x1="16.32" x2="16.32" y1="8.37" y2="7.153" gradientUnits="userSpaceOnUse"><stop class="lsu4c3nag"/><stop offset="1" class="er-tjgg3b"/></linearGradient><linearGradient id="iZlLq9V" x1="12.859" x2="19.974" y1="10.52" y2="10.52" gradientUnits="userSpaceOnUse"><stop class="pzfr262-g"/><stop offset="1" class="z-m0m1qra"/></linearGradient><linearGradient id="iTSTsSd" x1="12.91" x2="19.909" y1="19.563" y2="19.563" gradientUnits="userSpaceOnUse"><stop class="nbfjd2boi"/><stop offset="1" class="tweej22-r"/></linearGradient><linearGradient id="imQgNee" x1="14.357" x2="14.357" y1="19.844" y2="17.094" gradientUnits="userSpaceOnUse"><stop class="x5c8dtb7k"/><stop offset="1" class="l0lpjzp4p"/></linearGradient><linearGradient id="iSBZYcd" x1="26.926" x2="23.259" y1="17.285" y2="17.474" gradientUnits="userSpaceOnUse"><stop class="yuovncbrz"/><stop offset="1" class="gzgfd1blq"/></linearGradient><linearGradient id="i1iPuNd" x1="9.192" x2="9.192" y1="20.717" y2="18.085" gradientUnits="userSpaceOnUse"><stop class="l9-58_bja"/><stop offset="1" class="w_aihcbqx"/></linearGradient><linearGradient id="i4udJLe" x1="11.824" x2="8.929" y1="17.132" y2="17.691" gradientUnits="userSpaceOnUse"><stop class="l9-58_bja"/><stop offset="1" class="w_aihcbqx"/></linearGradient><linearGradient id="in05gud" x1="11.686" x2="10.78" y1="16.968" y2="17.318" gradientUnits="userSpaceOnUse"><stop class="hlyx2acyf"/><stop offset="1" class="f2y_xww7p"/></linearGradient><linearGradient id="iaiT2ew" x1="8.094" x2="8.094" y1="9.778" y2="12.996" gradientUnits="userSpaceOnUse"><stop class="ppweyo9ig"/><stop offset="1" class="jcjju3biw"/></linearGradient><linearGradient id="iEC8yKc" x1="7.919" x2="10.78" y1="8.987" y2="8.987" gradientUnits="userSpaceOnUse"><stop class="tlwijbc8y"/><stop offset="1" class="o534obbiv"/></linearGradient><linearGradient id="iopxbho" x1="7.576" x2="7.865" y1="8.47" y2="8.47" gradientUnits="userSpaceOnUse"><stop class="k1x4pggmy"/><stop offset=".806" class="c5k97ab8y"/></linearGradient><linearGradient id="iB3atVc" x1="23.825" x2="26.686" y1="8.941" y2="8.941" gradientUnits="userSpaceOnUse"><stop class="a46kwpd-t"/><stop offset="1" class="o534obbiv"/></linearGradient><linearGradient id="iYJjx7d" x1="23.482" x2="23.771" y1="8.425" y2="8.425" gradientUnits="userSpaceOnUse"><stop class="k1x4pggmy"/><stop offset=".806" class="c5k97ab8y"/></linearGradient><linearGradient id="irCNGcd" x1="16.002" x2="16.002" y1="18.094" y2="29.945" gradientUnits="userSpaceOnUse"><stop class="vwljeybjo"/><stop offset="1" class="azbukmb_u"/></linearGradient><linearGradient id="i1t9yJe" x1="10.279" x2="6.068" y1="8.445" y2="8.445" gradientUnits="userSpaceOnUse"><stop offset=".49" class="andakybwz"/><stop offset="1" class="y8fgw0-kz"/></linearGradient><linearGradient id="i99orwi" x1="26.149" x2="21.938" y1="8.445" y2="8.445" gradientUnits="userSpaceOnUse"><stop offset=".49" class="andakybwz"/><stop offset="1" class="y8fgw0-kz"/></linearGradient><filter id="i9zIRdd" width="7.495" height="6.858" x="12.502" y="2.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6868"/></filter><filter id="iZBC7cb" width="8.443" height="5.11" x="11.78" y="7.016" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.827451 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.588235 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6868" result="effect2_innerShadow_18_6868"/></filter><filter id="iHsmzZc" width="8.815" height="10.847" x="11.595" y="12.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.827451 0 0 0 0 0.843137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.505882 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6868" result="effect2_innerShadow_18_6868"/></filter><filter id="io0XKJd" width="9.147" height="9.612" x="19.586" y="9.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.160784 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6868"/></filter><filter id="igOOZde" width="9.147" height="9.612" x="3.771" y="9.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.270588 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6868"/></filter><filter id="iU6LLXd" width="3.352" height="9.668" x="7.656" y="10.003" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6868" stdDeviation=".25"/></filter><filter id="iIujPnd" width="26.689" height="11.852" x="2.707" y="18.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.631373 0 0 0 0 0.678431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_6868"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.831373 0 0 0 0 0.917647 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_6868" result="effect2_innerShadow_18_6868"/></filter><filter id="iDWFyWI" width="7.628" height="7.25" x="12.186" y="22.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6868" stdDeviation=".25"/></filter><filter id="iTlPbkJ" width="3.078" height="1.117" x="7.599" y="7.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6868" stdDeviation=".125"/></filter><filter id="ig4r7NS" width="3.078" height="1.117" x="23.469" y="7.5" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_6868" stdDeviation=".125"/></filter><radialGradient id="iV0yhvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37634 1.8878 0 16.002 14)" gradientUnits="userSpaceOnUse"><stop class="lr51vjsow"/><stop offset="1" class="tuymubc5t"/></radialGradient><radialGradient id="ifaJare" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.10938 7.48173 0 16 29.953)" gradientUnits="userSpaceOnUse"><stop class="lr51vjsow"/><stop offset="1" class="tuymubc5t"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:castle" /></template>
<style>
.a46kwpd-t {
  stop-color: var(--svg-color--38bee9, #38BEE9);
}

.andakybwz {
  stop-color: var(--svg-color--57c1e3, #57C1E3);
}

.ax-coj_na {
  fill: var(--svg-color--e0215d, #E0215D);
  d: path("M15.594 2.387c-1.15 2.574-2.928 6.21-3.092 6.566h6.995l-3.083-6.566c-.174-.389-.646-.389-.82 0");
}

.azbukmb_u {
  stop-color: var(--svg-color--d7c2dd, #D7C2DD);
}

.c5k97ab8y {
  stop-color: var(--svg-color--2ca2c8, #2CA2C8);
  stop-opacity: 0;
}

.clrkfzw9s {
  d: path("M7.576 7.268v2.198c0 .107.108.18.206.14l2.633-1.077a.15.15 0 0 0 .002-.277L7.784 7.13a.15.15 0 0 0-.208.138");
}

.cusot8b3f {
  d: path("M23.288 10.183a3064 3064 0 0 1-3.702 9.074l8.647.132l-3.74-9.205a.65.65 0 0 0-1.205-.001");
}

.er-tjgg3b {
  stop-color: var(--svg-color--d6214d, #D6214D);
  stop-opacity: 0;
}

.esch9bkuf {
  d: path("M15.594 2.387c-1.15 2.574-2.928 6.21-3.092 6.566h6.995l-3.083-6.566c-.174-.389-.646-.389-.82 0");
}

.f2y_xww7p {
  stop-color: var(--svg-color--c75a6c, #C75A6C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gzgfd1blq {
  stop-color: var(--svg-color--ff548e, #FF548E);
  stop-opacity: 0;
}

.hj6u20cdv {
  d: path("M7.473 10.183a3078 3078 0 0 1-3.702 9.074l8.647.132l-3.74-9.205a.65.65 0 0 0-1.205-.001");
}

.hlyx2acyf {
  stop-color: var(--svg-color--c75a6c, #C75A6C);
}

.hqiqkghpo {
  d: path("M12.938 26.781a3.062 3.062 0 0 1 6.125 0v3.172h-6.125z");
}

.ib_uut75k {
  fill: var(--svg-color--c2add6, #C2ADD6);
  d: path("M12.686 26.72a3.314 3.314 0 0 1 6.628 0v2.936h-6.628z");
}

.ibeh_mbmn {
  d: path("M16.765 14h-1.536v-.906a.774.774 0 0 1 1.546 0V14z");
}

.ivp13gbyw {
  fill: var(--svg-color--e8406d, #E8406D);
  d: path("m8.156 10.503l.444 8.668h1.908z");
}

.jcjju3biw {
  stop-color: var(--svg-color--c31c31, #C31C31);
  stop-opacity: 0;
}

.k1x4pggmy {
  stop-color: var(--svg-color--2ca5ca, #2CA5CA);
}

.l0lpjzp4p {
  stop-color: var(--svg-color--9e9598, #9E9598);
  stop-opacity: 0;
}

.l9-58_bja {
  stop-color: var(--svg-color--b51a44, #B51A44);
}

.lr51vjsow {
  stop-color: var(--svg-color--6a20f4, #6A20F4);
}

.lsu4c3nag {
  stop-color: var(--svg-color--d6214d, #D6214D);
}

.mr2xw04hq {
  d: path("M23.719 8.367h2.578L23.72 7.75z");
}

.n0rnws0ga {
  fill: var(--svg-color--e0215d, #E0215D);
  d: path("M23.288 10.183a3064 3064 0 0 1-3.702 9.074l8.647.132l-3.74-9.205a.65.65 0 0 0-1.205-.001");
}

.nbfjd2boi {
  stop-color: var(--svg-color--cab7bd, #CAB7BD);
}

.o534obbiv {
  stop-color: var(--svg-color--2272b6, #2272B6);
}

.onyhz3txt {
  d: path("M23.482 7.223v2.198c0 .107.108.18.207.139l2.632-1.076a.15.15 0 0 0 .002-.277L23.69 7.085a.15.15 0 0 0-.208.138");
}

.p4o9db_oe {
  d: path("M12.53 7.016a.5.5 0 0 0-.5.5v3.71a.9.9 0 0 0 .9.9h6.144a.9.9 0 0 0 .9-.9v-3.71a.5.5 0 0 0-.5-.5h-.593a.5.5 0 0 0-.5.5v.147a.5.5 0 0 1-.5.5h-.583a.5.5 0 0 1-.5-.5v-.147a.5.5 0 0 0-.5-.5h-.593a.5.5 0 0 0-.5.5v.147a.5.5 0 0 1-.5.5h-.582a.5.5 0 0 1-.5-.5v-.147a.5.5 0 0 0-.5-.5z");
}

.ppweyo9ig {
  stop-color: var(--svg-color--c31c31, #C31C31);
}

.pzfr262-g {
  stop-color: var(--svg-color--ccbac2, #CCBAC2);
}

.r4w8e6bye {
  d: path("M3.357 18.094a.5.5 0 0 0-.5.5v11.351h26.29V18.594a.5.5 0 0 0-.5-.5h-.579a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.51a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.579a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.51a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.579a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.51a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.578a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.511a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.578a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.511a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.578a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.511a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.578a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.51a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5h-.579a.5.5 0 0 0-.5.5v.125a.5.5 0 0 1-.5.5h-.51a.5.5 0 0 1-.5-.5v-.125a.5.5 0 0 0-.5-.5z");
}

.tlwijbc8y {
  stop-color: var(--svg-color--36bae4, #36BAE4);
}

.to7pjn83v {
  d: path("M7.849 8.367h2.578L7.849 7.75z");
}

.tuymubc5t {
  stop-color: var(--svg-color--4200bb, #4200BB);
}

.tweej22-r {
  stop-color: var(--svg-color--d2c1c5, #D2C1C5);
}

.uob74k9bp {
  d: path("M12.095 13.327a1.2 1.2 0 0 1 1.2-1.2h5.414a1.2 1.2 0 0 1 1.2 1.2v9.646h-7.814z");
}

.vwljeybjo {
  stop-color: var(--svg-color--cebbc6, #CEBBC6);
}

.w_aihcbqx {
  stop-color: var(--svg-color--b51a44, #B51A44);
  stop-opacity: 0;
}

.x5c8dtb7k {
  stop-color: var(--svg-color--9e9598, #9E9598);
}

.y8fgw0-kz {
  stop-color: var(--svg-color--57c1e3, #57C1E3);
  stop-opacity: 0;
}

.yuovncbrz {
  stop-color: var(--svg-color--ff548e, #FF548E);
}

.yx8451qay {
  fill: var(--svg-color--e0215d, #E0215D);
  d: path("M7.473 10.183a3078 3078 0 0 1-3.702 9.074l8.647.132l-3.74-9.205a.65.65 0 0 0-1.205-.001");
}

.z-m0m1qra {
  stop-color: var(--svg-color--d6c3cc, #D6C3CC);
}

</style>
