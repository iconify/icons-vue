<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ieDzxLL)"><path class="acov1ubsu"/></g><path fill="url(#iynFrhc)" class="b5jq_ezlb"/><path fill="url(#its1Kte)" class="b5jq_ezlb"/><path fill="url(#i2or1Dq)" class="b5jq_ezlb"/><path fill="url(#iub1Pib)" class="b5jq_ezlb"/><path fill="url(#iFpqUee)" class="b5jq_ezlb"/><path fill="url(#iodR0De)" class="b5jq_ezlb"/><g filter="url(#igCrwQd)"><path class="xcapgcidb"/></g><g filter="url(#inpqHYc)"><path class="fqpu5odbd"/></g><g filter="url(#iTGwGre)"><path class="tc559bb6g"/></g><g filter="url(#irmHERd)"><path fill="url(#iaksMne)" class="aquxd3kgw"/><path fill="url(#ivlKoMe)" class="aquxd3kgw"/></g><path fill="url(#idsxbNd)" class="aquxd3kgw"/><path fill="url(#iPj9NLb)" class="aquxd3kgw"/><path fill="url(#imErqxb)" class="aquxd3kgw"/><g filter="url(#iCQ0Ldc)"><rect transform="rotate(-3.35 8.64 14.061)" class="qn_44hbln"/></g><g filter="url(#ixkZ7eb)"><path fill="url(#inx4Qog)" class="u_d1acarq"/><path fill="url(#iXgqAHb)" class="u_d1acarq"/><path fill="url(#iHyqPib)" class="u_d1acarq"/><path fill="url(#izqVGgc)" class="u_d1acarq"/><path fill="url(#ibfdJzl)" class="u_d1acarq"/></g><g filter="url(#ilkaamd)"><rect fill="url(#iIgXbnd)" transform="rotate(-1.407 13.205 11.807)" class="wm4wylhyq"/></g><g filter="url(#idlyfrc)"><path fill="url(#iwfnXkM)" class="k8d006bbp"/></g><g filter="url(#i5DEATd)"><rect transform="rotate(-1.407 18.466 11.489)" class="go5xkxk7y"/></g><path fill="url(#i3Szmec)" class="itiy1kjju"/><path fill="url(#iOWDBQc)" class="itiy1kjju"/><path fill="url(#ifqxJre)" class="itiy1kjju"/><path fill="url(#ix4Q1zc)" class="itiy1kjju"/><g filter="url(#ifTxGre)"><path stroke="url(#iAkLSDd)" class="ju_0aac8r"/></g><g filter="url(#iDw4dUF)"><rect class="g4cniacyu"/></g><defs><radialGradient id="iynFrhc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.56216 -6.90397 4.82919 -4.5901 25.783 17.248)" gradientUnits="userSpaceOnUse"><stop class="xzjf40bpk"/><stop offset="1" class="h05xhwb1q"/></radialGradient><radialGradient id="its1Kte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86066 3.08361 -3.55273 -3.29586 20.767 21.186)" gradientUnits="userSpaceOnUse"><stop class="d-f75mbcd"/><stop offset="1" class="xrvq5pbbu"/></radialGradient><radialGradient id="iub1Pib" cx="0" cy="0" r="1" gradientTransform="matrix(-1 1.28124 -1.43471 -1.1198 24.502 3.875)" gradientUnits="userSpaceOnUse"><stop class="lg9oumb1w"/><stop offset="1" class="xsqd02wrs"/></radialGradient><radialGradient id="iFpqUee" cx="0" cy="0" r="1" gradientTransform="matrix(2.2172 -.61875 .85635 3.06859 20.137 12.398)" gradientUnits="userSpaceOnUse"><stop class="x4egsydtv"/><stop offset="1" class="zpvxyeb4z"/></radialGradient><radialGradient id="iodR0De" cx="0" cy="0" r="1" gradientTransform="scale(15.2373 18.5119)rotate(90 .202 .86)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="lr59ijbod"/><stop offset="1" class="rexkp13fp"/></radialGradient><radialGradient id="idsxbNd" cx="0" cy="0" r="1" gradientTransform="matrix(.22676 -2.36686 3.52277 .3375 7.93 20.23)" gradientUnits="userSpaceOnUse"><stop class="o_j8fybmu"/><stop offset="1" class="yb3181blf"/></radialGradient><radialGradient id="iPj9NLb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.05924 .64915 -1.06456 -1.73707 11.453 13.026)" gradientUnits="userSpaceOnUse"><stop class="hh_8_3o2d"/><stop offset="1" class="kpeh2-nfj"/></radialGradient><radialGradient id="iHyqPib" cx="0" cy="0" r="1" gradientTransform="matrix(.1227 -3.11745 7.27464 .28632 13.177 19.585)" gradientUnits="userSpaceOnUse"><stop class="he6xxbcij"/><stop offset="1" class="e-8jq7bts"/></radialGradient><radialGradient id="izqVGgc" cx="0" cy="0" r="1" gradientTransform="matrix(-.67768 .30875 -.56066 -1.2306 16.14 12.7)" gradientUnits="userSpaceOnUse"><stop class="mwdekok-a"/><stop offset="1" class="oaqun3bmj"/></radialGradient><radialGradient id="ibfdJzl" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68416 -.7271 .95657 -2.2157 16.142 18.249)" gradientUnits="userSpaceOnUse"><stop class="zz5svxbym"/><stop offset="1" class="uiixadcqh"/></radialGradient><radialGradient id="iIgXbnd" cx="0" cy="0" r="1" gradientTransform="rotate(91.407 .28 13.902)scale(7.23413 3.88646)" gradientUnits="userSpaceOnUse"><stop class="n93-w_b0d"/><stop offset="1" class="v48gtgb5o"/></radialGradient><radialGradient id="iOWDBQc" cx="0" cy="0" r="1" gradientTransform="matrix(3.40306 3.0913 -2.37051 2.60958 19.958 21.933)" gradientUnits="userSpaceOnUse"><stop class="jrwkkb9eu"/><stop offset="1" class="ocyvk_6bj"/></radialGradient><filter id="ieDzxLL" width="20.934" height="28.788" x="6.022" y="1.306" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.529412 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5628"/></filter><filter id="igCrwQd" width="14.516" height="10.203" x="12.595" y="13.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation="1.25"/></filter><filter id="inpqHYc" width="9.153" height="11.219" x="5.161" y="11.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation="1.25"/></filter><filter id="iTGwGre" width="9.825" height="12.747" x="9.013" y="10.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation="1.25"/></filter><filter id="irmHERd" width="5.431" height="8.136" x="6.022" y="12.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.607843 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5628"/></filter><filter id="iCQ0Ldc" width="4.869" height="7.227" x="7.189" y="12.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation=".75"/></filter><filter id="ixkZ7eb" width="5.272" height="8.719" x="10.869" y="10.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.6 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5628"/></filter><filter id="ilkaamd" width="5.019" height="8.302" x="11.729" y="10.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation=".75"/></filter><filter id="idlyfrc" width="5.414" height="9.427" x="16" y="10.158" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.74902 0 0 0 0 0.568627 0 0 0 0 0.447059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5628"/></filter><filter id="i5DEATd" width="5.045" height="9.019" x="16.99" y="9.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation=".75"/></filter><filter id="ifTxGre" width="8.894" height="7.703" x="17.451" y="15.234" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation=".625"/></filter><filter id="iDw4dUF" width="5.688" height="15.594" x="21.533" y="1.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5628" stdDeviation="1"/></filter><linearGradient id="i2or1Dq" x1="27.158" x2="23.424" y1="12.219" y2="12.219" gradientUnits="userSpaceOnUse"><stop class="xsxag_b4r"/><stop offset="1" class="o6qqqp3gw"/></linearGradient><linearGradient id="iaksMne" x1="11.453" x2="6.715" y1="14.579" y2="14.655" gradientUnits="userSpaceOnUse"><stop class="yecvorbsa"/><stop offset="1" class="htc0336yl"/></linearGradient><linearGradient id="ivlKoMe" x1="11.783" x2="10.021" y1="15.721" y2="15.837" gradientUnits="userSpaceOnUse"><stop class="jy7ersbyt"/><stop offset="1" class="a0916u3mn"/></linearGradient><linearGradient id="imErqxb" x1="6.022" x2="6.553" y1="16.391" y2="16.372" gradientUnits="userSpaceOnUse"><stop class="t5u_a-bkk"/><stop offset="1" class="upkja8mix"/></linearGradient><linearGradient id="inx4Qog" x1="15.897" x2="11.147" y1="14.438" y2="14.906" gradientUnits="userSpaceOnUse"><stop class="o7jgugfbs"/><stop offset="1" class="w59lbmb1o"/></linearGradient><linearGradient id="iXgqAHb" x1="16.462" x2="14.884" y1="14.753" y2="14.756" gradientUnits="userSpaceOnUse"><stop class="hzydfw14g"/><stop offset="1" class="ocrg1ubvd"/></linearGradient><linearGradient id="iwfnXkM" x1="16.99" x2="21.057" y1="13.868" y2="13.868" gradientUnits="userSpaceOnUse"><stop class="j65k49bwz"/><stop offset="1" class="zegnvv0_c"/></linearGradient><linearGradient id="i3Szmec" x1="24.512" x2="20.88" y1="17.178" y2="21.929" gradientUnits="userSpaceOnUse"><stop class="fvokeqbet"/><stop offset="1" class="e5zcqub-y"/></linearGradient><linearGradient id="ifqxJre" x1="22.893" x2="22.857" y1="26.284" y2="22.217" gradientUnits="userSpaceOnUse"><stop offset=".382" class="qcze5vx6e"/><stop offset="1" class="mxk571bku"/></linearGradient><linearGradient id="ix4Q1zc" x1="16.095" x2="19.737" y1="19.192" y2="19.192" gradientUnits="userSpaceOnUse"><stop class="s09hdnbjy"/><stop offset="1" class="rx360xbko"/></linearGradient><linearGradient id="iAkLSDd" x1="21.377" x2="24.885" y1="17.781" y2="20.397" gradientUnits="userSpaceOnUse"><stop offset=".452" class="be94hqsvp"/><stop offset="1" class="yrr26rb7v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:index-pointing-up-medium-light" /></template>
<style>
.a0916u3mn {
  stop-color: var(--svg-color--c88b61, #C88B61);
  stop-opacity: 0;
}

.acov1ubsu {
  fill: var(--svg-color--d89d90, #D89D90);
  d: path("M23.474 1.906a2.656 2.656 0 0 0-2.657 2.657v11.25H6.022v4.227c0 5.553 4.501 10.054 10.054 10.054c4.243 0 7.872-2.629 9.348-6.347l.003.003c1.015-2.39 1.015-6.703.844-7.86c-.104-.7-.134-1.205-.141-1.496V4.563a2.656 2.656 0 0 0-2.656-2.657");
}

.aquxd3kgw {
  d: path("M6.022 14.6c0-1.382 1.102-2.412 2.502-2.502c1.303-.063 2.597.735 2.707 2.323l.216 3.013c.108 1.51-1.3 2.796-2.815 2.796a2.61 2.61 0 0 1-2.61-2.61z");
}

.b5jq_ezlb {
  d: path("M23.474 1.906a2.656 2.656 0 0 0-2.657 2.657v11.25H6.022v4.227c0 5.553 4.501 10.054 10.054 10.054c4.243 0 7.872-2.629 9.348-6.347l.003.003c1.015-2.39 1.015-6.703.844-7.86c-.104-.7-.134-1.205-.141-1.496V4.563a2.656 2.656 0 0 0-2.656-2.657");
}

.be94hqsvp {
  stop-color: var(--svg-color--fecba9, #FECBA9);
}

.d-f75mbcd {
  stop-color: var(--svg-color--c68a82, #C68A82);
}

.e-8jq7bts {
  stop-color: var(--svg-color--ba777d, #BA777D);
  stop-opacity: 0;
}

.e5zcqub-y {
  stop-color: var(--svg-color--cf9489, #CF9489);
}

.fqpu5odbd {
  fill: var(--svg-color--914b49, #914B49);
  d: path("M7.66 16.103c0-1.057.843-1.844 1.914-1.913c.996-.048 1.986.563 2.07 1.776l.166 2.303c.082 1.155-.994 2.137-2.153 2.137a1.996 1.996 0 0 1-1.996-1.995z");
}

.ft5dv1b6b {
  fill: none;
}

.fvokeqbet {
  stop-color: var(--svg-color--f8c398, #F8C398);
}

.g4cniacyu {
  width: 1.688px;
  height: 11.594px;
  x: 23.533px;
  y: 3.531px;
  fill: var(--svg-color--ffcfa8, #FFCFA8);
  rx: 0.844px;
}

.go5xkxk7y {
  width: 1.945px;
  height: 6.02px;
  x: 18.466px;
  y: 11.489px;
  fill: var(--svg-color--ffd0ab, #FFD0AB);
  rx: 0.973px;
}

.h05xhwb1q {
  stop-color: var(--svg-color--ffcea5, #FFCEA5);
  stop-opacity: 0;
}

.he6xxbcij {
  stop-color: var(--svg-color--ba777d, #BA777D);
}

.hh_8_3o2d {
  stop-color: var(--svg-color--ac7249, #AC7249);
}

.htc0336yl {
  stop-color: var(--svg-color--cc9b78, #CC9B78);
}

.hzydfw14g {
  stop-color: var(--svg-color--ce946d, #CE946D);
}

.itiy1kjju {
  d: path("M18.608 15.281c-1.388 0-2.513 1.161-2.513 2.594s1.125 2.594 2.513 2.594h.105c.821 0 1.64.317 2.066 1.02a6 6 0 0 1 .875 3.136c0 .878-.187 1.712-.521 2.463c2.598-.625 4.531-2.995 4.531-5.822c0-2.492-1.597-4.686-3.734-5.587a3.4 3.4 0 0 0-1.007-.288z");
}

.j65k49bwz {
  stop-color: var(--svg-color--cc9373, #CC9373);
}

.jrwkkb9eu {
  stop-color: var(--svg-color--b6707b, #B6707B);
}

.ju_0aac8r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M19.327 17.11c1.201 0 3.21 0 3.945.944c1.076 1.052 1.138 2.589 1.198 3.009");
}

.jy7ersbyt {
  stop-color: var(--svg-color--c98e64, #C98E64);
}

.k8d006bbp {
  d: path("M16 13.008c0-1.574 1.212-2.85 2.707-2.85s2.707 1.276 2.707 2.85v3.727c0 1.574-1.212 2.85-2.707 2.85S16 18.853 16 17.135z");
}

.kpeh2-nfj {
  stop-color: var(--svg-color--ac7249, #AC7249);
  stop-opacity: 0;
}

.lg9oumb1w {
  stop-color: var(--svg-color--ffcfa8, #FFCFA8);
}

.lr59ijbod {
  stop-color: var(--svg-color--b77396, #B77396);
  stop-opacity: 0;
}

.mwdekok-a {
  stop-color: var(--svg-color--c38b63, #C38B63);
}

.mxk571bku {
  stop-color: var(--svg-color--d89d90, #D89D90);
  stop-opacity: 0;
}

.n93-w_b0d {
  stop-color: var(--svg-color--f7c5a7, #F7C5A7);
}

.o_j8fybmu {
  stop-color: var(--svg-color--bb7881, #BB7881);
}

.o6qqqp3gw {
  stop-color: var(--svg-color--f3c29d, #F3C29D);
  stop-opacity: 0;
}

.o7jgugfbs {
  stop-color: var(--svg-color--e9bc95, #E9BC95);
}

.oaqun3bmj {
  stop-color: var(--svg-color--c38b63, #C38B63);
  stop-opacity: 0;
}

.ocrg1ubvd {
  stop-color: var(--svg-color--ce946d, #CE946D);
  stop-opacity: 0;
}

.ocyvk_6bj {
  stop-color: var(--svg-color--b6707b, #B6707B);
  stop-opacity: 0;
}

.qcze5vx6e {
  stop-color: var(--svg-color--d89d90, #D89D90);
}

.qn_44hbln {
  width: 1.722px;
  height: 4.231px;
  x: 8.64px;
  y: 14.061px;
  fill: var(--svg-color--f7c4a4, #F7C4A4);
  rx: 0.861px;
}

.rexkp13fp {
  stop-color: var(--svg-color--b77396, #B77396);
}

.rx360xbko {
  stop-color: var(--svg-color--bf866a, #BF866A);
  stop-opacity: 0;
}

.s09hdnbjy {
  stop-color: var(--svg-color--bf866a, #BF866A);
}

.t5u_a-bkk {
  stop-color: var(--svg-color--db9f87, #DB9F87);
}

.tc559bb6g {
  fill: var(--svg-color--914b49, #914B49);
  d: path("M11.513 15.658c0-1.294 1.08-2.343 2.412-2.343c1.333 0 2.413 1.049 2.413 2.343v3.062c0 1.294-1.08 2.343-2.413 2.343s-2.218-.672-2.218-2.084z");
}

.u_d1acarq {
  d: path("M10.87 13.502a2.636 2.636 0 0 1 5.272 0v3.447a2.636 2.636 0 0 1-2.636 2.636c-1.456 0-2.424-.756-2.424-2.345z");
}

.uiixadcqh {
  stop-color: var(--svg-color--a25d4e, #A25D4E);
  stop-opacity: 0;
}

.upkja8mix {
  stop-color: var(--svg-color--db9f87, #DB9F87);
  stop-opacity: 0;
}

.v48gtgb5o {
  stop-color: var(--svg-color--f7c5a7, #F7C5A7);
  stop-opacity: 0;
}

.w59lbmb1o {
  stop-color: var(--svg-color--cc9975, #CC9975);
}

.wm4wylhyq {
  width: 1.936px;
  height: 5.303px;
  x: 13.205px;
  y: 11.807px;
  rx: 0.968px;
}

.x4egsydtv {
  stop-color: var(--svg-color--c27d50, #C27D50);
}

.xcapgcidb {
  fill: var(--svg-color--914b49, #914B49);
  d: path("M15.095 18.875c0-1.433 1.125-2.594 2.513-2.594l2.315.11c.346.042.69.14 1.008.288c1.91.805 3.388 2.644 3.68 4.805h-6.585a3 3 0 0 0-.313-.015h-.105c-1.388 0-2.513-1.162-2.513-2.594");
}

.xrvq5pbbu {
  stop-color: var(--svg-color--c68a82, #C68A82);
  stop-opacity: 0;
}

.xsqd02wrs {
  stop-color: var(--svg-color--ffcfa8, #FFCFA8);
  stop-opacity: 0;
}

.xsxag_b4r {
  stop-color: var(--svg-color--f3c29d, #F3C29D);
}

.xzjf40bpk {
  stop-color: var(--svg-color--ffcea5, #FFCEA5);
}

.yb3181blf {
  stop-color: var(--svg-color--bb7881, #BB7881);
  stop-opacity: 0;
}

.yecvorbsa {
  stop-color: var(--svg-color--e1b38f, #E1B38F);
}

.yrr26rb7v {
  stop-color: var(--svg-color--fecba9, #FECBA9);
  stop-opacity: 0;
}

.zegnvv0_c {
  stop-color: var(--svg-color--f8c297, #F8C297);
}

.zpvxyeb4z {
  stop-color: var(--svg-color--c27d50, #C27D50);
  stop-opacity: 0;
}

.zz5svxbym {
  stop-color: var(--svg-color--a25d4e, #A25D4E);
}

</style>
