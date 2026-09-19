<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iJOKGic)"><path fill="url(#iC6vu8d)" class="qaus0dbio"/><path fill="url(#iC6vu8d)" class="bqapvpbvi"/></g><g filter="url(#iIdkFvc)"><path stroke="url(#iFDJ55k)" class="xc69dzbwn"/></g><g filter="url(#iT55k7z)"><path stroke="url(#ijdgTtb)" class="j0ryhhd_r"/></g><g filter="url(#iyu2b5c)"><path clip-rule="evenodd" class="g-drl-7-v"/></g><g filter="url(#iYlH5ob)" class="atjk8mbde"><path stroke="url(#ivLUOkc)" class="asq9evb7g"/><path stroke="url(#imDs1Ed)" class="asq9evb7g"/></g><path stroke="url(#ibACfCe)" class="bg2dwi3bs"/><g filter="url(#ikyNxlc)"><path stroke="url(#ipOOExb)" class="fk8tfjbzp"/></g><path stroke="url(#iZw1jMb)" class="wgop-i2hs"/><path stroke="url(#i7UBM8b)" class="s04u_c8pk"/><path fill="url(#i2K59Bb)" class="m4i5x7vqc"/><path fill="url(#iOWx18d)" class="m4i5x7vqc"/><path fill="url(#iVbQQqb)" class="yc1a1fahw"/><g filter="url(#ilQJ1Ae)"><path stroke="url(#iLcROxd)" class="pbel0efui"/></g><defs><linearGradient id="iC6vu8d" x1="11.698" x2="4.76" y1="20.475" y2="27.538" gradientUnits="userSpaceOnUse"><stop class="y_3l-vbtt"/><stop offset="1" class="clv9cxboe"/></linearGradient><linearGradient id="iFDJ55k" x1="4.901" x2="4.901" y1="7.881" y2="13.065" gradientUnits="userSpaceOnUse"><stop class="d13t4eb8k"/><stop offset="1" class="ym21rwf_b"/></linearGradient><linearGradient id="ijdgTtb" x1="23.343" x2="17.909" y1="27.631" y2="28.772" gradientUnits="userSpaceOnUse"><stop class="cu92w5bzp"/><stop offset="1" class="fpcd9f49a"/></linearGradient><linearGradient id="ivLUOkc" x1="5.573" x2="15.456" y1="6.819" y2="8.725" gradientUnits="userSpaceOnUse"><stop class="k8787pr0p"/><stop offset="1" class="vig5ajbhx"/></linearGradient><linearGradient id="imDs1Ed" x1="25.698" x2="23.135" y1="27.975" y2="13.163" gradientUnits="userSpaceOnUse"><stop class="jactt4dcc"/><stop offset="1" class="gzj35rv_m"/></linearGradient><linearGradient id="ibACfCe" x1="24.01" x2="5.417" y1="8.538" y2="26.663" gradientUnits="userSpaceOnUse"><stop offset=".217" class="q9bpr6bzf"/><stop offset=".497" class="po2xgnnlf"/></linearGradient><linearGradient id="ipOOExb" x1="6.76" x2="21.948" y1="25.85" y2="10.1" gradientUnits="userSpaceOnUse"><stop class="udngybmqn"/><stop offset="1" class="lh4it_bgo"/></linearGradient><linearGradient id="iZw1jMb" x1="27.045" x2="24.139" y1="25.85" y2="28.786" gradientUnits="userSpaceOnUse"><stop class="s05kpdb0e"/><stop offset="1" class="m7ktwebfc"/></linearGradient><linearGradient id="i7UBM8b" x1="7.073" x2="4.198" y1="5.788" y2="8.694" gradientUnits="userSpaceOnUse"><stop class="s05kpdb0e"/><stop offset="1" class="ktp6jsb3y"/></linearGradient><linearGradient id="i2K59Bb" x1="28.115" x2="24.404" y1="8.691" y2="3.588" gradientUnits="userSpaceOnUse"><stop offset=".564" class="i9vw4e44v"/><stop offset="1" class="eiwa4rb3f"/></linearGradient><linearGradient id="iOWx18d" x1="24.47" x2="25.34" y1="8.823" y2="7.929" gradientUnits="userSpaceOnUse"><stop offset=".024" class="vfwwo2bfr"/><stop offset="1" class="g3jwhzd1e"/></linearGradient><linearGradient id="iLcROxd" x1="25.2" x2="15.524" y1="15.646" y2="8.223" gradientUnits="userSpaceOnUse"><stop class="cub1-9bnr"/><stop offset="1" class="ebr90jb3g"/></linearGradient><filter id="iJOKGic" width="10.95" height="10.864" x="1.545" y="19.944" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.380392 0 0 0 0 0.294118 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24195"/></filter><filter id="iIdkFvc" width="1.406" height="20.125" x="4.198" y="7.381" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.686275 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24195"/></filter><filter id="iT55k7z" width="19.094" height="1.219" x="5.104" y="26.913" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.686275 0 0 0 0 0.823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24195"/></filter><filter id="iyu2b5c" width="25.534" height="25.425" x="3.126" y="3.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy="-1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.423529 0 0 0 0 0.227451 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24195"/></filter><filter id="iYlH5ob" width="23.284" height="22.456" x="4.064" y="5.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24195" stdDeviation=".325"/></filter><filter id="ikyNxlc" width="17.031" height="17" x="4.667" y="10.788" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24195" stdDeviation=".25"/></filter><filter id="ilQJ1Ae" width="8.665" height="8.245" x="16.47" y="7.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24195" stdDeviation=".5"/></filter><radialGradient id="iVbQQqb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.58262 -5.69969 3.36603 -2.11577 24.006 15.384)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="lqnwg3rpw"/><stop offset="1" class="nfiai9-hs"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:bow-and-arrow" /></template>
<style>
.asq9evb7g {
  d: path("M5.214 6.819c.656.583 1.967 1.714 3.656 2.156c3.406.89 6.86-2.266 11.656 2.203c3.46 3.223 3.672 5.672 3.547 7.797s-.688 4.875 2.125 8");
}

.atjk8mbde {
  stroke-linecap: round;
}

.bg2dwi3bs {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m5.417 27.038l20.28-20.22");
}

.bqapvpbvi {
  d: path("m11.178 27.69l-2.66 2.606a1.79 1.79 0 0 1-2.522-2.54l6.499-6.539l-.43 4.609a3 3 0 0 1-.887 1.864");
}

.clv9cxboe {
  stop-color: var(--svg-color--705ca5, #705CA5);
}

.cu92w5bzp {
  stop-color: var(--svg-color--beabcd, #BEABCD);
}

.cub1-9bnr {
  stop-color: var(--svg-color--ffdf6e, #FFDF6E);
}

.d13t4eb8k {
  stop-color: var(--svg-color--bbadc6, #BBADC6);
}

.ebr90jb3g {
  stop-color: var(--svg-color--ffdf6e, #FFDF6E);
  stop-opacity: 0;
}

.eiwa4rb3f {
  stop-color: var(--svg-color--cbc8d5, #CBC8D5);
}

.fk8tfjbzp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m5.417 27.038l15.53-15.5");
}

.fpcd9f49a {
  stop-color: var(--svg-color--ded0eb, #DED0EB);
}

.ft5dv1b6b {
  fill: none;
}

.g-drl-7-v {
  fill: var(--svg-color--7e574d, #7E574D);
  fill-rule: evenodd;
  d: path("M3.606 5.807a1.9 1.9 0 0 1 2.682-.158c.65.577 1.665 1.422 2.875 1.738c.51.134 1.088.134 1.886.042c.216-.025.484-.063.782-.105c.623-.087 1.374-.193 2.038-.235c1.105-.07 2.35-.014 3.698.43c1.349.445 2.697 1.243 4.067 2.519c1.948 1.815 2.965 3.571 3.423 5.288c.417 1.557.33 2.964.269 3.965l-.013.202c-.02.335-.066.775-.106 1.165a35 35 0 0 0-.06.6c-.048.554-.064 1.062-.008 1.565c.103.931.468 2.018 1.722 3.284a1.9 1.9 0 1 1-2.7 2.674c-1.857-1.875-2.601-3.757-2.799-5.54c-.095-.855-.059-1.64-.001-2.308c.03-.351.059-.616.085-.85a15 15 0 0 0 .08-.91c.063-1.07.113-1.92-.14-2.866c-.246-.923-.831-2.08-2.343-3.489c-1.028-.958-1.91-1.441-2.665-1.69s-1.485-.296-2.27-.247c-.544.034-.99.099-1.494.172a36 36 0 0 1-1.131.151c-.957.11-2.09.171-3.281-.14c-2.169-.568-3.775-1.986-4.438-2.575a1.9 1.9 0 0 1-.158-2.682");
}

.g3jwhzd1e {
  stop-color: var(--svg-color--cdc7da, #CDC7DA);
  stop-opacity: 0;
}

.gzj35rv_m {
  stop-color: var(--svg-color--a18079, #A18079);
  stop-opacity: 0;
}

.i9vw4e44v {
  stop-color: var(--svg-color--e0daee, #E0DAEE);
}

.j0ryhhd_r {
  stroke-linecap: round;
  d: path("m5.604 27.413l18.094.218");
}

.jactt4dcc {
  stop-color: var(--svg-color--a18079, #A18079);
}

.k8787pr0p {
  stop-color: var(--svg-color--8c6661, #8C6661);
}

.ktp6jsb3y {
  stop-color: var(--svg-color--baaec6, #BAAEC6);
}

.lh4it_bgo {
  stop-color: var(--svg-color--eaab85, #EAAB85);
}

.lqnwg3rpw {
  stop-color: var(--svg-color--eebb3a, #EEBB3A);
}

.m4i5x7vqc {
  d: path("M26.683 11.034L21.48 5.902a.65.65 0 0 1 .292-1.091l6.807-1.782a.65.65 0 0 1 .798.776l-1.604 6.913a.65.65 0 0 1-1.09.316");
}

.m7ktwebfc {
  stop-color: var(--svg-color--b7a1cc, #B7A1CC);
}

.nfiai9-hs {
  stop-color: var(--svg-color--e3a63f, #E3A63F);
}

.pbel0efui {
  stroke-linecap: round;
  d: path("M17.97 9.062c.95.367 1.952.985 3.021 1.98c1.273 1.186 2.106 2.267 2.644 3.265");
}

.po2xgnnlf {
  stop-color: var(--svg-color--de9e6d, #DE9E6D);
}

.q9bpr6bzf {
  stop-color: var(--svg-color--cb8b6e, #CB8B6E);
}

.qaus0dbio {
  d: path("m4.663 21.26l-2.606 2.66a1.79 1.79 0 0 0 2.54 2.523l6.538-6.5l-4.608.43a3 3 0 0 0-1.864.887");
}

.s04u_c8pk {
  stroke-linecap: round;
  d: path("m3.892 8.558l2.837-2.77");
}

.s05kpdb0e {
  stop-color: var(--svg-color--f3eef8, #F3EEF8);
}

.udngybmqn {
  stop-color: var(--svg-color--eaac87, #EAAC87);
}

.vfwwo2bfr {
  stop-color: var(--svg-color--c0b0d1, #C0B0D1);
}

.vig5ajbhx {
  stop-color: var(--svg-color--8c6661, #8C6661);
  stop-opacity: 0;
}

.wgop-i2hs {
  stroke-linecap: round;
  d: path("m23.907 28.573l2.79-2.723");
}

.xc69dzbwn {
  stroke-linecap: round;
  d: path("m4.698 7.881l.406 19.125");
}

.y_3l-vbtt {
  stop-color: var(--svg-color--8a6cc0, #8A6CC0);
}

.yc1a1fahw {
  d: path("M21.294 16c-.291-.868-.902-1.925-2.25-3.182c-1.03-.958-1.912-1.441-2.666-1.69A5 5 0 0 0 16 11.02l1.06-3.651q.25.066.507.15c1.349.445 2.697 1.243 4.067 2.519c1.692 1.577 2.682 3.11 3.213 4.61z");
}

.ym21rwf_b {
  stop-color: var(--svg-color--dfd4ea, #DFD4EA);
}

</style>
