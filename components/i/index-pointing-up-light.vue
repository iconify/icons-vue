<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ik2PFif)"><path class="qa0cueb6c"/></g><path fill="url(#iLNJwDe)" class="eomtocyaq"/><path fill="url(#iXDD3ub)" class="eomtocyaq"/><path fill="url(#i5CCWYd)" class="eomtocyaq"/><path fill="url(#ix4q39c)" class="eomtocyaq"/><path fill="url(#i5794Ud)" class="eomtocyaq"/><path fill="url(#i7JieRb)" class="eomtocyaq"/><path fill="url(#iEm1hud)" class="eomtocyaq"/><g filter="url(#iSEiv7c)"><path class="h6r0n1b3v"/></g><g filter="url(#iGYpute)"><path class="q4_zmy76s"/></g><g filter="url(#iZgEP7j)"><path class="ggdujytyu"/></g><g filter="url(#iyB14Md)"><path fill="url(#iGgTxTE)" class="x32ai7b6d"/><path fill="url(#iyuo6Le)" class="x32ai7b6d"/></g><path fill="url(#iSLZXWb)" class="x32ai7b6d"/><path fill="url(#iYT82Yd)" class="x32ai7b6d"/><path fill="url(#isjKxod)" class="x32ai7b6d"/><g filter="url(#ifOzqod)"><rect transform="rotate(-3.35 8.302 14.061)" class="i5fq8sb8h"/></g><g filter="url(#ix4rQzb)"><path fill="url(#iwzTQxd)" class="lmmhnpbne"/><path fill="url(#iNDIxQe)" class="lmmhnpbne"/><path fill="url(#iJBlfFe)" class="lmmhnpbne"/><path fill="url(#iPY6Mqb)" class="lmmhnpbne"/><path fill="url(#iSajMic)" class="lmmhnpbne"/></g><g filter="url(#iPa1zee)"><rect fill="url(#iyZ6c4c)" transform="rotate(-1.407 12.867 11.807)" class="ha9pd0-sq"/></g><g filter="url(#i3M8bud)"><path fill="url(#i2JqITc)" class="mp7-bha1d"/></g><g filter="url(#idbDCqc)"><rect transform="rotate(-1.407 18.129 11.489)" class="lf5i86bno"/></g><path fill="url(#i2gPivb)" class="veyerqx9j"/><path fill="url(#iMW1rRq)" class="veyerqx9j"/><path fill="url(#iL7jpgY)" class="veyerqx9j"/><path fill="url(#iP1wHPe)" class="veyerqx9j"/><g filter="url(#iAsSw6K)"><path stroke="url(#iC9h3pd)" class="d5xlfib-d"/></g><g filter="url(#iwD3O5d)"><rect class="xc47svb7l"/></g><defs><radialGradient id="iLNJwDe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56216 -6.90397 4.82919 -4.5901 25.445 17.248)" gradientUnits="userSpaceOnUse"><stop class="zl2ys_buy"/><stop offset="1" class="se18qgbat"/></radialGradient><radialGradient id="iXDD3ub" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86066 3.08361 -3.55273 -3.29586 20.43 21.186)" gradientUnits="userSpaceOnUse"><stop class="eot_rsa5c"/><stop offset="1" class="dafvthzpv"/></radialGradient><radialGradient id="ix4q39c" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.28124 -1.43471 -1.1198 24.164 3.875)" gradientUnits="userSpaceOnUse"><stop class="g73iv-bvy"/><stop offset="1" class="alsobs70x"/></radialGradient><radialGradient id="i5794Ud" cx="0" cy="0" r="1" gradientTransform="matrix(2.2172 -.61875 .85635 3.06859 19.8 12.398)" gradientUnits="userSpaceOnUse"><stop class="jj4d61bwi"/><stop offset="1" class="ordpuw84x"/></radialGradient><radialGradient id="i7JieRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.5119 -15.2373 0 15.862 12.2)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="ybxyifbtq"/><stop offset="1" class="yys8_4b8d"/></radialGradient><radialGradient id="iEm1hud" cx="0" cy="0" r="1" gradientTransform="matrix(.85162 0 0 13.342 20.202 8.018)" gradientUnits="userSpaceOnUse"><stop class="fuz3rib_r"/><stop offset="1" class="whkzwsb4f"/></radialGradient><radialGradient id="iSLZXWb" cx="0" cy="0" r="1" gradientTransform="matrix(.22676 -2.36686 3.52277 .3375 7.592 20.23)" gradientUnits="userSpaceOnUse"><stop class="yt67fsblr"/><stop offset="1" class="f9fo5bkqc"/></radialGradient><radialGradient id="iYT82Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05924 .64915 -1.06456 -1.73707 11.115 13.026)" gradientUnits="userSpaceOnUse"><stop class="wbk86yb2g"/><stop offset="1" class="y0wiihb-h"/></radialGradient><radialGradient id="iJBlfFe" cx="0" cy="0" r="1" gradientTransform="matrix(.1227 -3.11745 7.27464 .28632 12.84 19.585)" gradientUnits="userSpaceOnUse"><stop class="wcmtsdb9t"/><stop offset="1" class="vo560ubaq"/></radialGradient><radialGradient id="iPY6Mqb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67768 .30875 -.56066 -1.2306 15.803 12.7)" gradientUnits="userSpaceOnUse"><stop class="pzz1ij28i"/><stop offset="1" class="pgd25fbey"/></radialGradient><radialGradient id="iSajMic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68416 -.7271 .95657 -2.2157 15.804 18.249)" gradientUnits="userSpaceOnUse"><stop class="r3xondc_a"/><stop offset="1" class="ywn-ktxpx"/></radialGradient><radialGradient id="iyZ6c4c" cx="0" cy="0" r="1" gradientTransform="rotate(91.407 .111 13.737)scale(7.23413 3.88646)" gradientUnits="userSpaceOnUse"><stop class="ae5vg5b9k"/><stop offset="1" class="vma3fs41g"/></radialGradient><radialGradient id="iMW1rRq" cx="0" cy="0" r="1" gradientTransform="rotate(41.969 -18.81 36.469)scale(4.62267 3.54127)" gradientUnits="userSpaceOnUse"><stop class="rmu4m7bqz"/><stop offset="1" class="vzorc1bxh"/></radialGradient><filter id="ik2PFif" width="20.934" height="28.788" x="5.684" y="1.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8125 0 0 0 0 0.584446 0 0 0 0 0.548437 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5644"/></filter><filter id="iSEiv7c" width="14.516" height="10.203" x="12.258" y="13.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation="1.25"/></filter><filter id="iGYpute" width="9.153" height="11.219" x="4.823" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation="1.25"/></filter><filter id="iZgEP7j" width="9.825" height="12.747" x="8.675" y="10.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation="1.25"/></filter><filter id="iyB14Md" width="5.431" height="8.136" x="5.684" y="12.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.67451 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5644"/></filter><filter id="ifOzqod" width="4.869" height="7.227" x="6.851" y="12.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation=".75"/></filter><filter id="ix4rQzb" width="5.272" height="8.719" x="10.532" y="10.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.584314 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5644"/></filter><filter id="iPa1zee" width="5.019" height="8.302" x="11.391" y="10.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation=".75"/></filter><filter id="i3M8bud" width="5.414" height="9.427" x="15.662" y="10.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.670588 0 0 0 0 0.564706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5644"/></filter><filter id="idbDCqc" width="5.045" height="9.019" x="16.652" y="9.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation=".75"/></filter><filter id="iAsSw6K" width="8.894" height="7.703" x="17.114" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation=".625"/></filter><filter id="iwD3O5d" width="5.688" height="15.594" x="21.195" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5644" stdDeviation="1"/></filter><linearGradient id="i5CCWYd" x1="26.82" x2="23.086" y1="12.219" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="p2luicaxb"/><stop offset="1" class="ypy_6dbzj"/></linearGradient><linearGradient id="iGgTxTE" x1="11.115" x2="6.377" y1="14.579" y2="14.655" gradientUnits="userSpaceOnUse"><stop class="wgd7y5bnh"/><stop offset="1" class="yrfpopb3s"/></linearGradient><linearGradient id="iyuo6Le" x1="11.445" x2="9.683" y1="15.721" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="nnj20v5id"/><stop offset="1" class="e-x64cbbq"/></linearGradient><linearGradient id="isjKxod" x1="5.684" x2="6.216" y1="16.391" y2="16.372" gradientUnits="userSpaceOnUse"><stop class="i_w-uabpc"/><stop offset="1" class="iegtlx2wq"/></linearGradient><linearGradient id="iwzTQxd" x1="15.559" x2="10.809" y1="14.438" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="vvor_51wf"/><stop offset="1" class="j70j9obny"/></linearGradient><linearGradient id="iNDIxQe" x1="16.124" x2="14.546" y1="14.753" y2="14.756" gradientUnits="userSpaceOnUse"><stop class="jui5iobbr"/><stop offset="1" class="e7xb5bbxt"/></linearGradient><linearGradient id="i2JqITc" x1="15.997" x2="20.72" y1="13.868" y2="13.868" gradientUnits="userSpaceOnUse"><stop class="e6z4cq6hh"/><stop offset="1" class="gu-qx1k5y"/></linearGradient><linearGradient id="i2gPivb" x1="24.163" x2="20.54" y1="17.178" y2="21.963" gradientUnits="userSpaceOnUse"><stop class="yd2apzb-o"/><stop offset="1" class="cuog6z_ci"/></linearGradient><linearGradient id="iL7jpgY" x1="22.527" x2="22.492" y1="26.284" y2="22.217" gradientUnits="userSpaceOnUse"><stop offset=".382" class="zkzlqibot"/><stop offset="1" class="eay7wcb6n"/></linearGradient><linearGradient id="iP1wHPe" x1="15.662" x2="19.341" y1="19.192" y2="19.192" gradientUnits="userSpaceOnUse"><stop class="bxmktlb9q"/><stop offset="1" class="waca33bfb"/></linearGradient><linearGradient id="iC9h3pd" x1="21.039" x2="24.547" y1="17.781" y2="20.397" gradientUnits="userSpaceOnUse"><stop offset=".452" class="ojk4lcxhk"/><stop offset="1" class="ktleplbow"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-up-light" /></template>
<style>
.ae5vg5b9k {
  stop-color: var(--svg-color--ffdac1, #FFDAC1);
}

.alsobs70x {
  stop-color: var(--svg-color--ffe2c5, #FFE2C5);
  stop-opacity: 0;
}

.bxmktlb9q {
  stop-color: var(--svg-color--d19780, #D19780);
}

.cuog6z_ci {
  stop-color: var(--svg-color--e1aaa2, #E1AAA2);
}

.d5xlfib-d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M18.989 17.11c1.201 0 3.21 0 3.946.944c1.075 1.052 1.137 2.589 1.198 3.009");
}

.dafvthzpv {
  stop-color: var(--svg-color--d9a09a, #D9A09A);
  stop-opacity: 0;
}

.e-x64cbbq {
  stop-color: var(--svg-color--dc9f7b, #DC9F7B);
  stop-opacity: 0;
}

.e6z4cq6hh {
  stop-color: var(--svg-color--e3a589, #E3A589);
}

.e7xb5bbxt {
  stop-color: var(--svg-color--e5a384, #E5A384);
  stop-opacity: 0;
}

.eay7wcb6n {
  stop-color: var(--svg-color--e7afa7, #E7AFA7);
  stop-opacity: 0;
}

.eomtocyaq {
  d: path("M23.136 1.906a2.656 2.656 0 0 0-2.656 2.656v11.25H5.684v4.228c0 5.553 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.347l.003.003c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.562a2.656 2.656 0 0 0-2.657-2.656");
}

.eot_rsa5c {
  stop-color: var(--svg-color--d9a09a, #D9A09A);
}

.f9fo5bkqc {
  stop-color: var(--svg-color--c5868d, #C5868D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fuz3rib_r {
  stop-color: var(--svg-color--efb195, #EFB195);
}

.g73iv-bvy {
  stop-color: var(--svg-color--ffe2c5, #FFE2C5);
}

.ggdujytyu {
  fill: var(--svg-color--ab6362, #AB6362);
  d: path("M11.175 15.658c0-1.294 1.08-2.343 2.412-2.343c1.333 0 2.413 1.049 2.413 2.343v3.062c0 1.294-1.08 2.343-2.413 2.343s-2.218-.672-2.218-2.084z");
}

.gu-qx1k5y {
  stop-color: var(--svg-color--ffdebe, #FFDEBE);
}

.h6r0n1b3v {
  fill: var(--svg-color--ab6362, #AB6362);
  d: path("M14.758 18.875c0-1.433 1.124-2.594 2.512-2.594l2.315.11c.346.042.69.14 1.008.288c1.91.805 3.389 2.644 3.68 4.805h-6.585a3 3 0 0 0-.313-.015h-.105c-1.388 0-2.512-1.162-2.512-2.594");
}

.ha9pd0-sq {
  width: 1.936px;
  height: 5.303px;
  x: 12.867px;
  y: 11.807px;
  rx: 0.968px;
}

.i_w-uabpc {
  stop-color: var(--svg-color--efb59b, #EFB59B);
}

.i5fq8sb8h {
  width: 1.722px;
  height: 4.231px;
  x: 8.302px;
  y: 14.061px;
  fill: var(--svg-color--ffdbc4, #FFDBC4);
  rx: 0.861px;
}

.iegtlx2wq {
  stop-color: var(--svg-color--efb59b, #EFB59B);
  stop-opacity: 0;
}

.j70j9obny {
  stop-color: var(--svg-color--e6ab93, #E6AB93);
}

.jj4d61bwi {
  stop-color: var(--svg-color--e19871, #E19871);
}

.jui5iobbr {
  stop-color: var(--svg-color--e5a384, #E5A384);
}

.ktleplbow {
  stop-color: var(--svg-color--ffe1c8, #FFE1C8);
  stop-opacity: 0;
}

.lf5i86bno {
  width: 1.945px;
  height: 6.02px;
  x: 18.129px;
  y: 11.489px;
  fill: var(--svg-color--ffe5c6, #FFE5C6);
  rx: 0.973px;
}

.lmmhnpbne {
  d: path("M10.532 13.502a2.636 2.636 0 1 1 5.272 0v3.447a2.636 2.636 0 0 1-2.636 2.636c-1.456 0-2.424-.756-2.424-2.345z");
}

.mp7-bha1d {
  d: path("M15.662 13.008c0-1.574 1.212-2.85 2.707-2.85s2.707 1.276 2.707 2.85v3.727c0 1.574-1.212 2.85-2.707 2.85s-2.707-.732-2.707-2.45z");
}

.nnj20v5id {
  stop-color: var(--svg-color--dc9f7b, #DC9F7B);
}

.ojk4lcxhk {
  stop-color: var(--svg-color--ffe1c8, #FFE1C8);
}

.ordpuw84x {
  stop-color: var(--svg-color--e19871, #E19871);
  stop-opacity: 0;
}

.p2luicaxb {
  stop-color: var(--svg-color--ffd7bb, #FFD7BB);
}

.pgd25fbey {
  stop-color: var(--svg-color--b97a56, #B97A56);
  stop-opacity: 0;
}

.pzz1ij28i {
  stop-color: var(--svg-color--b97a56, #B97A56);
}

.q4_zmy76s {
  fill: var(--svg-color--ab6362, #AB6362);
  d: path("M7.323 16.103c0-1.057.843-1.844 1.914-1.913c.996-.048 1.986.563 2.07 1.776l.165 2.303c.083 1.155-.994 2.137-2.153 2.137a1.996 1.996 0 0 1-1.996-1.995z");
}

.qa0cueb6c {
  fill: var(--svg-color--e7afa7, #E7AFA7);
  d: path("M23.136 1.906a2.656 2.656 0 0 0-2.656 2.656v11.25H5.684v4.228c0 5.553 4.502 10.054 10.054 10.054c4.243 0 7.873-2.629 9.348-6.347l.003.003c1.016-2.39 1.016-6.703.844-7.86a12 12 0 0 1-.14-1.496V4.562a2.656 2.656 0 0 0-2.657-2.656");
}

.r3xondc_a {
  stop-color: var(--svg-color--bb7261, #BB7261);
}

.rmu4m7bqz {
  stop-color: var(--svg-color--c2838c, #C2838C);
}

.se18qgbat {
  stop-color: var(--svg-color--ffe6c6, #FFE6C6);
  stop-opacity: 0;
}

.veyerqx9j {
  d: path("M18.2 15.281c-1.402 0-2.538 1.161-2.538 2.594s1.136 2.594 2.537 2.594h.128c.816 0 1.63.313 2.059 1.008c.564.914.89 1.993.89 3.148c0 .878-.188 1.712-.526 2.463a5.98 5.98 0 0 0 4.576-5.822c0-2.492-1.613-4.686-3.77-5.587a3.4 3.4 0 0 0-1.018-.288z");
}

.vma3fs41g {
  stop-color: var(--svg-color--ffdac1, #FFDAC1);
  stop-opacity: 0;
}

.vo560ubaq {
  stop-color: var(--svg-color--c6878b, #C6878B);
  stop-opacity: 0;
}

.vvor_51wf {
  stop-color: var(--svg-color--f3bb9d, #F3BB9D);
}

.vzorc1bxh {
  stop-color: var(--svg-color--c2838c, #C2838C);
  stop-opacity: 0;
}

.waca33bfb {
  stop-color: var(--svg-color--d19780, #D19780);
  stop-opacity: 0;
}

.wbk86yb2g {
  stop-color: var(--svg-color--c88b67, #C88B67);
}

.wcmtsdb9t {
  stop-color: var(--svg-color--c6878b, #C6878B);
}

.wgd7y5bnh {
  stop-color: var(--svg-color--f1c3a7, #F1C3A7);
}

.whkzwsb4f {
  stop-color: var(--svg-color--efb195, #EFB195);
  stop-opacity: 0;
}

.x32ai7b6d {
  d: path("M5.684 14.6c0-1.382 1.102-2.412 2.503-2.502c1.302-.063 2.596.735 2.707 2.323l.215 3.013c.108 1.51-1.3 2.796-2.815 2.796a2.61 2.61 0 0 1-2.61-2.61z");
}

.xc47svb7l {
  width: 1.688px;
  height: 11.594px;
  x: 23.195px;
  y: 3.531px;
  fill: var(--svg-color--ffe3c8, #FFE3C8);
  rx: 0.844px;
}

.y0wiihb-h {
  stop-color: var(--svg-color--c88b67, #C88B67);
  stop-opacity: 0;
}

.ybxyifbtq {
  stop-color: var(--svg-color--ba7d98, #BA7D98);
  stop-opacity: 0;
}

.yd2apzb-o {
  stop-color: var(--svg-color--ffdcbb, #FFDCBB);
}

.ypy_6dbzj {
  stop-color: var(--svg-color--ffd7bb, #FFD7BB);
  stop-opacity: 0;
}

.yrfpopb3s {
  stop-color: var(--svg-color--e0aa93, #E0AA93);
}

.yt67fsblr {
  stop-color: var(--svg-color--c5868d, #C5868D);
}

.ywn-ktxpx {
  stop-color: var(--svg-color--bb7261, #BB7261);
  stop-opacity: 0;
}

.yys8_4b8d {
  stop-color: var(--svg-color--ba7d98, #BA7D98);
}

.zkzlqibot {
  stop-color: var(--svg-color--e7afa7, #E7AFA7);
}

.zl2ys_buy {
  stop-color: var(--svg-color--ffe6c6, #FFE6C6);
}

</style>
