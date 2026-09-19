<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iV8oXBc)" class="lcs0hlkod"/><path fill="url(#i1OgaVU)" class="lcs0hlkod"/><path fill="url(#i3K1ove)" class="lcs0hlkod"/><g filter="url(#i0W7V6d)"><path fill="url(#iRdbiOd)" class="qypap3bmd"/><path fill="url(#iIrAT4b)" class="qypap3bmd"/><path fill="url(#i7DbxBc)" class="qypap3bmd"/><path fill="url(#iDUPbSc)" class="qypap3bmd"/></g><g filter="url(#iCyr53p)"><path fill="url(#i8SAtPd)" class="iz-np2bnf"/><path stroke="url(#iTwfb5b)" class="s8j-acclo"/></g><g filter="url(#iBI8fje)"><path class="lt2tziiym"/></g><g filter="url(#ikFt87G)"><rect fill="url(#iLTEcKc)" class="kdr_9uogw"/></g><g filter="url(#ihFIbjc)"><rect fill="url(#iNYy8wc)" class="mtmdpsv8d"/></g><g filter="url(#i1rdQBe)"><path class="dgcutnw-q"/></g><g filter="url(#iwMznbc)"><path fill="url(#iLj8YVb)" class="fx7ta_rwt"/><path fill="url(#iBCewte)" class="fx7ta_rwt"/><path fill="url(#ilPGXwd)" class="fx7ta_rwt"/></g><g filter="url(#iokZDYb)"><rect class="g8pxlsk7v"/></g><path fill="url(#iPuQ3oc)" class="r4igwsbwm"/><path fill="url(#iFBSeYp)" class="r4igwsbwm"/><path fill="url(#it8f7ze)" class="r4igwsbwm"/><defs><radialGradient id="i3K1ove" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.95639 5.62268 0 15.511 29.887)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="r2t4_lbss"/><stop offset="1" class="kgtji58_q"/></radialGradient><radialGradient id="iIrAT4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.0625 -18.8502 0 16 8.313)" gradientUnits="userSpaceOnUse"><stop offset=".062" class="i32nthb7d"/><stop offset="1" class="vmveirb9e"/></radialGradient><radialGradient id="i7DbxBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.3125 -2.64062 0 18.494 14.313)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="uo-9febtk"/><stop offset="1" class="q6bod2byz"/></radialGradient><radialGradient id="iDUPbSc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.25 11.669 1.28)scale(3.76883 1.66127)" gradientUnits="userSpaceOnUse"><stop offset=".112" class="ryzg5u1hk"/><stop offset="1" class="gl4piacvm"/></radialGradient><radialGradient id="iTwfb5b" cx="0" cy="0" r="1" gradientTransform="rotate(125.738 4.647 9.961)scale(9.4165 3.1675)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="w0agh__gw"/><stop offset="1" class="zn8uzcb-g"/></radialGradient><radialGradient id="ilPGXwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.21875 1.64063 0 19.447 11.938)" gradientUnits="userSpaceOnUse"><stop offset=".071" class="qti0jtb5s"/><stop offset="1" class="ife76c-0z"/></radialGradient><radialGradient id="iPuQ3oc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.34375 3.06638 0 18.447 16.188)" gradientUnits="userSpaceOnUse"><stop class="e8aou4znm"/><stop offset="1" class="vya-oyh8q"/></radialGradient><radialGradient id="iFBSeYp" cx="0" cy="0" r="1" gradientTransform="matrix(-3.59375 .65627 -.78454 -4.29614 20.478 13.75)" gradientUnits="userSpaceOnUse"><stop offset=".548" class="xhu7qbcbp"/><stop offset="1" class="b0ibeccrb"/></radialGradient><radialGradient id="it8f7ze" cx="0" cy="0" r="1" gradientTransform="matrix(1.70313 -1.03125 .76786 1.26814 20.087 13.016)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="lu51tzbik"/><stop offset="1" class="bda8j7spa"/></radialGradient><linearGradient id="iV8oXBc" x1="16.822" x2="13.186" y1="29.887" y2="29.887" gradientUnits="userSpaceOnUse"><stop class="q2664bbii"/><stop offset=".42" class="v3rncsbye"/><stop offset=".774" class="gxbwcacfp"/></linearGradient><linearGradient id="i1OgaVU" x1="18.103" x2="17.353" y1="29.887" y2="29.887" gradientUnits="userSpaceOnUse"><stop class="w8uut-baw"/><stop offset="1" class="zrqwy0bgb"/></linearGradient><linearGradient id="iRdbiOd" x1="20.525" x2="20.525" y1="24.931" y2="11.25" gradientUnits="userSpaceOnUse"><stop offset=".743" class="divkuacvo"/><stop offset="1" class="zel_y-bno"/></linearGradient><linearGradient id="i8SAtPd" x1="9.128" x2="9.128" y1="9.587" y2="24.438" gradientUnits="userSpaceOnUse"><stop class="cokxxk8kk"/><stop offset="1" class="eaioehbkd"/></linearGradient><linearGradient id="iLTEcKc" x1="9.481" x2="9.481" y1="20.014" y2="21.945" gradientUnits="userSpaceOnUse"><stop class="p-8oo_6lt"/><stop offset="1" class="ab3wd3maw"/></linearGradient><linearGradient id="iNYy8wc" x1="7.114" x2="10.915" y1="21.256" y2="21.256" gradientUnits="userSpaceOnUse"><stop class="x0-1wibft"/><stop offset="1" class="eeduirb-n"/></linearGradient><linearGradient id="iLj8YVb" x1="18.103" x2="19.931" y1="8.625" y2="8.625" gradientUnits="userSpaceOnUse"><stop class="h7zeo4btt"/><stop offset="1" class="b1gpw7bpm"/></linearGradient><linearGradient id="iBCewte" x1="18.782" x2="18.782" y1="2.141" y2="3.844" gradientUnits="userSpaceOnUse"><stop class="o96k1ubhi"/><stop offset="1" class="fj9naqvwy"/></linearGradient><filter id="i0W7V6d" width="24.313" height="16.283" x="4.044" y="8.648" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.356863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21971"/></filter><filter id="iCyr53p" width="10.987" height="16.36" x="3.634" y="8.828" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21971" stdDeviation=".25"/></filter><filter id="iBI8fje" width="6.68" height="5.119" x="19.291" y="2.891" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.14902 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21971"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.14902 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21971" result="effect2_innerShadow_18_21971"/></filter><filter id="ikFt87G" width="6.205" height="2.431" x="6.129" y="20.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.321569 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21971"/></filter><filter id="ihFIbjc" width="5.484" height="1.364" x="6.614" y="20.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21971" stdDeviation=".25"/></filter><filter id="i1rdQBe" width="6.161" height=".817" x="19.237" y="3.193" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21971" stdDeviation=".075"/></filter><filter id="iwMznbc" width="2.597" height="11.066" x="17.634" y="1.841" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.3"/><feGaussianBlur stdDeviation=".425"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.427451 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21971"/></filter><filter id="iokZDYb" width="1.616" height="10.852" x="18.424" y="2.391" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21971" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:closed-mailbox-with-raised-flag" /></template>
<style>
.ab3wd3maw {
  stop-color: var(--svg-color--1872e0, #1872E0);
}

.b0ibeccrb {
  stop-color: var(--svg-color--60569a, #60569A);
}

.b1gpw7bpm {
  stop-color: var(--svg-color--b9afc7, #B9AFC7);
}

.bda8j7spa {
  stop-color: var(--svg-color--afabb5, #AFABB5);
  stop-opacity: 0;
}

.cokxxk8kk {
  stop-color: var(--svg-color--3a7df2, #3A7DF2);
}

.dgcutnw-q {
  stroke: var(--svg-color--f667a3, #F667A3);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M19.462 3.418h5.313c.096.005.31.086.398.367");
}

.divkuacvo {
  stop-color: var(--svg-color--4396ff, #4396FF);
}

.e8aou4znm {
  stop-color: var(--svg-color--9f71cd, #9F71CD);
}

.eaioehbkd {
  stop-color: var(--svg-color--3d7dff, #3D7DFF);
}

.eeduirb-n {
  stop-color: var(--svg-color--568ff7, #568FF7);
  stop-opacity: 0;
}

.fj9naqvwy {
  stop-color: var(--svg-color--8c8893, #8C8893);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx7ta_rwt {
  d: path("M17.634 3.29a1.149 1.149 0 0 1 2.297 0v9.616h-2.297z");
}

.g8pxlsk7v {
  width: 0.616px;
  height: 9.852px;
  x: 18.924px;
  y: 2.891px;
  fill: var(--svg-color--c0b9ca, #C0B9CA);
  rx: 0.308px;
}

.gl4piacvm {
  stop-color: var(--svg-color--2476c7, #2476C7);
  stop-opacity: 0;
}

.gxbwcacfp {
  stop-color: var(--svg-color--5e3a43, #5E3A43);
}

.h7zeo4btt {
  stop-color: var(--svg-color--9a85b2, #9A85B2);
}

.i32nthb7d {
  stop-color: var(--svg-color--4d70a0, #4D70A0);
}

.ife76c-0z {
  stop-color: var(--svg-color--c3bfca, #C3BFCA);
  stop-opacity: 0;
}

.iz-np2bnf {
  d: path("M5.303 24.438h7.65a.927.927 0 0 0 .919-.936v-8.779c0-2.736-2.019-5.136-4.744-5.136c-2.572-.163-4.744 1.915-4.744 5.136v8.779c0 .517.412.936.92.936");
}

.kdr_9uogw {
  width: 5.705px;
  height: 1.931px;
  x: 6.629px;
  y: 20.014px;
  rx: 0.966px;
}

.kgtji58_q {
  stop-color: var(--svg-color--5a3a46, #5A3A46);
}

.lcs0hlkod {
  d: path("M13.186 24.93h4.65v4.957h-4.65z");
}

.lt2tziiym {
  fill: var(--svg-color--f64092, #F64092);
  d: path("M19.29 3.14h5.38a.8.8 0 0 1 .8.8v3.12a.8.8 0 0 1-.8.8h-5.38z");
}

.lu51tzbik {
  stop-color: var(--svg-color--cbc4d6, #CBC4D6);
}

.mtmdpsv8d {
  width: 4.484px;
  height: 0.364px;
  x: 7.114px;
  y: 21.074px;
  rx: 0.182px;
}

.o96k1ubhi {
  stop-color: var(--svg-color--8c8893, #8C8893);
}

.p-8oo_6lt {
  stop-color: var(--svg-color--3b6bf1, #3B6BF1);
}

.q2664bbii {
  stop-color: var(--svg-color--8f616c, #8F616C);
}

.q6bod2byz {
  stop-color: var(--svg-color--4398ff, #4398FF);
  stop-opacity: 0;
}

.qti0jtb5s {
  stop-color: var(--svg-color--c3bfca, #C3BFCA);
}

.qypap3bmd {
  d: path("M4.044 14.548a5.5 5.5 0 0 1 5.5-5.5h12.912a5.5 5.5 0 0 1 5.5 5.5v9.383a1 1 0 0 1-1 1H5.044a1 1 0 0 1-1-1z");
}

.r2t4_lbss {
  stop-color: var(--svg-color--632f53, #632F53);
  stop-opacity: 0;
}

.r4igwsbwm {
  d: path("M17.634 11.938c-.631.398-.883 1.185-.883 2.091c0 1.309.668 2.37 1.976 2.37a2.37 2.37 0 0 0 2.37-2.37c0-.906-.415-1.693-1.162-2.091z");
}

.ryzg5u1hk {
  stop-color: var(--svg-color--114ca0, #114CA0);
}

.s8j-acclo {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.303 24.563h7.65c.578 0 1.044-.477 1.044-1.061v-8.779c0-2.79-2.06-5.259-4.865-5.26c-2.654-.167-4.873 1.982-4.873 5.26v8.779c0 .584.465 1.06 1.044 1.06Z");
}

.uo-9febtk {
  stop-color: var(--svg-color--2356e3, #2356E3);
}

.v3rncsbye {
  stop-color: var(--svg-color--7d4261, #7D4261);
}

.vmveirb9e {
  stop-color: var(--svg-color--3d93eb, #3D93EB);
  stop-opacity: 0;
}

.vya-oyh8q {
  stop-color: var(--svg-color--9994a1, #9994A1);
}

.w0agh__gw {
  stop-color: var(--svg-color--5c9dff, #5C9DFF);
}

.w8uut-baw {
  stop-color: var(--svg-color--855a5d, #855A5D);
}

.x0-1wibft {
  stop-color: var(--svg-color--568ff7, #568FF7);
}

.xhu7qbcbp {
  stop-color: var(--svg-color--73679f, #73679F);
  stop-opacity: 0;
}

.zel_y-bno {
  stop-color: var(--svg-color--59a1ff, #59A1FF);
}

.zn8uzcb-g {
  stop-color: var(--svg-color--5c9dff, #5C9DFF);
  stop-opacity: 0;
}

.zrqwy0bgb {
  stop-color: var(--svg-color--855a5d, #855A5D);
  stop-opacity: 0;
}

</style>
