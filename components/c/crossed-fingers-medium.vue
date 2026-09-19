<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ieZ6Mrm)" class="agu6_rs1h"/><path fill="url(#i20Eyuc)" class="agu6_rs1h"/><path fill="url(#iIj7uCO)" class="agu6_rs1h"/><path fill="url(#isvJhZd)" class="qa8ylsbmy"/><path fill="url(#iW0lz3K)" class="agu6_rs1h"/><path fill="url(#iMw1i9c)" class="agu6_rs1h"/><g filter="url(#igiAHnN)"><path class="whu-6q9-s"/></g><g filter="url(#iAuSgud)"><path class="icvi_dbud"/><path fill="url(#io3kuMd)" class="k9_5y2bmu"/><path fill="url(#i25iPxe)" class="k9_5y2bmu"/><path fill="url(#imE7bzd)" class="k9_5y2bmu"/></g><g filter="url(#isT7Yac)"><path class="o7rbp5qib"/></g><g filter="url(#iAvRT5b)"><path class="w92m0ew7o"/></g><g filter="url(#i27rjYd)"><path class="b157f-hbi"/></g><path class="bqvqpng6i"/><path fill="url(#itomSnc)" class="vvx90yqyz"/><path fill="url(#iV5zGAc)" class="vvx90yqyz"/><path fill="url(#i7F63cm)" class="vvx90yqyz"/><path class="v4ip-ttng"/><path fill="url(#iKwR62b)" class="xjq13x_cu"/><path fill="url(#iY8vVDd)" class="xjq13x_cu"/><path fill="url(#ijkolVb)" class="xjq13x_cu"/><g filter="url(#iD6pvgc)"><path class="qq2xvsbus"/></g><path fill="url(#id3hl3c)" class="ykv0gywid"/><path fill="url(#iIiowDc)" class="ykv0gywid"/><path fill="url(#iIwGgTd)" class="ykv0gywid"/><path fill="url(#inzgdJe)" class="ykv0gywid"/><g filter="url(#i0WxFgc)"><rect fill="url(#iYhMtmd)" class="foh1yus9a"/></g><g filter="url(#idbv26b)"><rect class="bfx80z_sk"/></g><path fill="url(#ibDZgEd)" class="wlc_0fj7m"/><path fill="url(#iS5mNqe)" class="wlc_0fj7m"/><g filter="url(#iHbIl5d)"><path stroke="url(#ijGVKdd)" class="z0vpmcszf"/></g><path fill="url(#iYo93Ae)" class="yugveyzaq"/><path fill="url(#i8550Ld)" class="yugveyzaq"/><defs><radialGradient id="i20Eyuc" cx="0" cy="0" r="1" gradientTransform="rotate(-145.784 13.273 1.69)scale(7.55811 20.3298)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="i30xlmdae"/><stop offset="1" class="d5h_2seyf"/></radialGradient><radialGradient id="iIj7uCO" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44892 .96594 -7.83612 -11.75422 20.112 11.329)" gradientUnits="userSpaceOnUse"><stop offset=".331" class="qf0fwq23q"/><stop offset="1" class="s8scx1bpu"/><stop offset="1" class="dsptssbyz"/></radialGradient><radialGradient id="isvJhZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0767 .48941 -3.97031 -8.73467 20.002 11.897)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="i51kugboq"/><stop offset=".652" class="ntmtwq-4s"/></radialGradient><radialGradient id="iW0lz3K" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.26935 1.63468 0 19.183 14.561)" gradientUnits="userSpaceOnUse"><stop class="gyenk48bs"/><stop offset="1" class="fb720cbij"/></radialGradient><radialGradient id="iMw1i9c" cx="0" cy="0" r="1" gradientTransform="rotate(128.409 12.36 7.347)scale(3.53833 4.6463)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="bmkks1b4a"/><stop offset="1" class="j0appubyf"/></radialGradient><radialGradient id="io3kuMd" cx="0" cy="0" r="1" gradientTransform="matrix(9.31253 10.06253 -14.13907 13.08522 6.674 14.29)" gradientUnits="userSpaceOnUse"><stop class="ih-9ecb_y"/><stop offset="1" class="vaqq6obaf"/></radialGradient><radialGradient id="i25iPxe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.53125 0 0 -2.78125 20.69 20.5)" gradientUnits="userSpaceOnUse"><stop class="blmgsbc5b"/><stop offset="1" class="z43dy1qxy"/></radialGradient><radialGradient id="imE7bzd" cx="0" cy="0" r="1" gradientTransform="matrix(.61472 -8.4666 16.95696 1.23117 14.35 29.684)" gradientUnits="userSpaceOnUse"><stop class="domhp0d7r"/><stop offset="1" class="g09328pji"/></radialGradient><radialGradient id="iV5zGAc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.14698 -4.32661 0 8.6 10.25)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="brhhngbvt"/><stop offset="1" class="k_f7ilbeo"/></radialGradient><radialGradient id="i7F63cm" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 0 0 -3.75 10.86 12.459)" gradientUnits="userSpaceOnUse"><stop offset=".423" class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iKwR62b" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.80191 -4.23235 0 13.16 9.322)" gradientUnits="userSpaceOnUse"><stop offset=".661" class="by13ilbaa"/><stop offset="1" class="q62993b5f"/></radialGradient><radialGradient id="ijkolVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.16274 -.82077 1.14253 -1.61856 15.584 15.637)" gradientUnits="userSpaceOnUse"><stop offset=".174" class="n5j1fzehk"/><stop offset="1" class="zetiuj7eb"/></radialGradient><radialGradient id="id3hl3c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36442 6.31216 -14.65791 -5.49058 23.369 14.66)" gradientUnits="userSpaceOnUse"><stop offset=".165" class="lr2dwibkw"/><stop offset="1" class="t4jtfac7z"/></radialGradient><radialGradient id="iIwGgTd" cx="0" cy="0" r="1" gradientTransform="matrix(2.53066 1.77831 -3.77054 5.36574 14.644 14.372)" gradientUnits="userSpaceOnUse"><stop class="pyknw39we"/><stop offset="1" class="p9it8mr-k"/></radialGradient><radialGradient id="inzgdJe" cx="0" cy="0" r="1" gradientTransform="matrix(.90292 -.5788 .91809 1.43221 15.373 17.67)" gradientUnits="userSpaceOnUse"><stop class="iwt4g8j9j"/><stop offset="1" class="z6zvxkbqp"/></radialGradient><radialGradient id="ibDZgEd" cx="0" cy="0" r="1" gradientTransform="matrix(17.92986 -4.46025 4.67365 18.78772 8.234 18.119)" gradientUnits="userSpaceOnUse"><stop offset=".876" class="u69ow0smy"/><stop offset="1" class="xxc65wsdn"/></radialGradient><radialGradient id="iS5mNqe" cx="0" cy="0" r="1" gradientTransform="matrix(-16.56248 5.49997 -10.06467 -30.30848 22.986 17.996)" gradientUnits="userSpaceOnUse"><stop offset=".808" class="mk1t0gbzg"/><stop offset="1" class="urk3w6bnk"/></radialGradient><radialGradient id="iYo93Ae" cx="0" cy="0" r="1" gradientTransform="matrix(2.53891 -1.50963 7.16354 12.04777 18.252 9.404)" gradientUnits="userSpaceOnUse"><stop class="uzauj2_4e"/><stop offset="1" class="ip5w0ybbi"/></radialGradient><radialGradient id="i8550Ld" cx="0" cy="0" r="1" gradientTransform="matrix(1.99614 3.81794 -5.7135 2.9872 16.272 1.837)" gradientUnits="userSpaceOnUse"><stop class="j5hn0w6yp"/><stop offset="1" class="lf8olxkfy"/></radialGradient><filter id="igiAHnN" width="9.747" height="10.915" x="17.071" y="1.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation="1"/></filter><filter id="iAuSgud" width="20.855" height="28.601" x="5.809" y="1.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.364706 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2239"/></filter><filter id="isT7Yac" width="14.735" height="10.475" x="11.692" y="12.865" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation="1"/></filter><filter id="iAvRT5b" width="7.158" height="9.171" x="5.362" y="8.459" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation=".5"/></filter><filter id="i27rjYd" width="9.128" height="11.13" x="7.814" y="8.232" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation="1"/></filter><filter id="iD6pvgc" width="11.372" height="22.961" x="15.717" y=".988" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation="1"/></filter><filter id="i0WxFgc" width="3.86" height="6.984" x="7.204" y="8.996" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation=".625"/></filter><filter id="idbv26b" width="5.193" height="8.957" x="11.616" y="7.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation=".875"/></filter><filter id="iHbIl5d" width="11.553" height="9.797" x="15.722" y="12.76" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2239" stdDeviation="1"/></filter><linearGradient id="ieZ6Mrm" x1="18.305" x2="25.014" y1="12.237" y2="3.045" gradientUnits="userSpaceOnUse"><stop class="lsmwm5l6o"/><stop offset="1" class="as4iu0b4t"/></linearGradient><linearGradient id="itomSnc" x1="5.809" x2="8.141" y1="13.115" y2="13.115" gradientUnits="userSpaceOnUse"><stop class="mamqa4bzl"/><stop offset="1" class="l0d7ryfzq"/></linearGradient><linearGradient id="iY8vVDd" x1="9.93" x2="12.694" y1="12.62" y2="12.62" gradientUnits="userSpaceOnUse"><stop class="txlar6bix"/><stop offset="1" class="rmqpg9b0t"/></linearGradient><linearGradient id="iIiowDc" x1="23.364" x2="23.364" y1="22.989" y2="19.912" gradientUnits="userSpaceOnUse"><stop class="b37z6tixq"/><stop offset="1" class="bbqpltegm"/></linearGradient><linearGradient id="iYhMtmd" x1="9.483" x2="9.483" y1="14.317" y2="10.246" gradientUnits="userSpaceOnUse"><stop class="dl6lnsb-n"/><stop offset="1" class="l_il3lbsl"/></linearGradient><linearGradient id="ijGVKdd" x1="17.652" x2="27.22" y1="15.76" y2="20.125" gradientUnits="userSpaceOnUse"><stop class="o_bue_bdr"/><stop offset="1" class="svdxfhbbg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-fingers-medium" /></template>
<style>
.agu6_rs1h {
  d: path("M20.798 2.67c-2.137 2.178-4.641 5.148-5.516 8.633l-.223 2.765h5.031c1.032-1.823 2.813-5.32 4.575-7.305s.555-3.777-.067-4.308a2.68 2.68 0 0 0-3.8.215");
}

.as4iu0b4t {
  stop-color: var(--svg-color--be937a, #BE937A);
}

.b157f-hbi {
  fill: var(--svg-color--6e4044, #6E4044);
  d: path("M9.814 12.673c0-1.348 1.148-2.441 2.564-2.441s2.564 1.093 2.564 2.441v2.247c0 1.348-1.148 2.441-2.564 2.441s-2.564-1.093-2.564-2.441z");
}

.b37z6tixq {
  stop-color: var(--svg-color--a57575, #A57575);
}

.bbqpltegm {
  stop-color: var(--svg-color--a57575, #A57575);
  stop-opacity: 0;
}

.bfx80z_sk {
  width: 1.693px;
  height: 5.457px;
  x: 13.366px;
  y: 9.273px;
  fill: var(--svg-color--d0a88c, #D0A88C);
  rx: 0.847px;
}

.blmgsbc5b {
  stop-color: var(--svg-color--b5877e, #B5877E);
}

.bmkks1b4a {
  stop-color: var(--svg-color--c8a384, #C8A384);
}

.bqvqpng6i {
  fill: var(--svg-color--a7836a, #A7836A);
  d: path("M5.81 11.424c0-1.43 1.249-2.59 2.79-2.59c1.542 0 2.791 1.16 2.791 2.59v2.383c0 1.43-1.25 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.brhhngbvt {
  stop-color: var(--svg-color--91596b, #91596B);
  stop-opacity: 0;
}

.by13ilbaa {
  stop-color: var(--svg-color--935a6e, #935A6E);
  stop-opacity: 0;
}

.d5h_2seyf {
  stop-color: var(--svg-color--8f7664, #8F7664);
}

.dl6lnsb-n {
  stop-color: var(--svg-color--bb968b, #BB968B);
}

.domhp0d7r {
  stop-color: var(--svg-color--ae797e, #AE797E);
}

.dsptssbyz {
  stop-color: var(--svg-color--6c4538, #6C4538);
  stop-opacity: 0;
}

.fb720cbij {
  stop-color: var(--svg-color--b79276, #B79276);
  stop-opacity: 0;
}

.foh1yus9a {
  width: 1.36px;
  height: 4.484px;
  x: 8.454px;
  y: 10.246px;
  rx: 0.68px;
}

.ft5dv1b6b {
  fill: none;
}

.g09328pji {
  stop-color: var(--svg-color--ae797e, #AE797E);
  stop-opacity: 0;
}

.gyenk48bs {
  stop-color: var(--svg-color--b79276, #B79276);
}

.i30xlmdae {
  stop-color: var(--svg-color--8f7664, #8F7664);
  stop-opacity: 0;
}

.i51kugboq {
  stop-color: var(--svg-color--846250, #846250);
}

.icvi_dbud {
  fill: var(--svg-color--a47474, #A47474);
  d: path("m5.997 20.559l-.188-5.114V13.89h14.469c.01-.844-1.844-4.116-4.254-7.32c-1.422-1.891-.62-3.566.516-4.305c1.476-.961 3.05-.16 3.945.898c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.398-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.138-9.658-9.125");
}

.ih-9ecb_y {
  stop-color: var(--svg-color--90665f, #90665F);
}

.ip5w0ybbi {
  stop-color: var(--svg-color--774e37, #774E37);
  stop-opacity: 0;
}

.iwt4g8j9j {
  stop-color: var(--svg-color--8f6361, #8F6361);
}

.j0appubyf {
  stop-color: var(--svg-color--c8a384, #C8A384);
  stop-opacity: 0;
}

.j5hn0w6yp {
  stop-color: var(--svg-color--90725d, #90725D);
}

.k_f7ilbeo {
  stop-color: var(--svg-color--91596b, #91596B);
}

.k9_5y2bmu {
  d: path("m5.997 20.559l-.188-5.114V13.89h14.469c.01-.844-1.844-4.116-4.254-7.32c-1.422-1.891-.62-3.566.516-4.305c1.476-.961 3.05-.16 3.945.898c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.398-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.138-9.658-9.125");
}

.l_il3lbsl {
  stop-color: var(--svg-color--b88b7e, #B88B7E);
  stop-opacity: 0;
}

.l0d7ryfzq {
  stop-color: var(--svg-color--90715b, #90715B);
  stop-opacity: 0;
}

.lf8olxkfy {
  stop-color: var(--svg-color--90725d, #90725D);
  stop-opacity: 0;
}

.lr2dwibkw {
  stop-color: var(--svg-color--b99272, #B99272);
}

.lsmwm5l6o {
  stop-color: var(--svg-color--815942, #815942);
}

.mamqa4bzl {
  stop-color: var(--svg-color--90715b, #90715B);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mk1t0gbzg {
  stop-color: var(--svg-color--956468, #956468);
  stop-opacity: 0;
}

.n5j1fzehk {
  stop-color: var(--svg-color--5c342e, #5C342E);
}

.ntmtwq-4s {
  stop-color: var(--svg-color--846250, #846250);
  stop-opacity: 0;
}

.o_bue_bdr {
  stop-color: var(--svg-color--cfa590, #CFA590);
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o7rbp5qib {
  fill: var(--svg-color--6e4044, #6E4044);
  d: path("M16.829 14.865c-1.733 0-3.137 1.246-3.137 2.782s1.404 2.783 3.137 2.783h1.67c2.526 0 3.18.132 3.38.359l1.535-.178c1.23 1.4.996.652.996-1.122v-.505c0-2.84-1.56-3.711-4.65-4.071a3.6 3.6 0 0 0-.583-.048z");
}

.p9it8mr-k {
  stop-color: var(--svg-color--8d6b54, #8D6B54);
  stop-opacity: 0;
}

.pyknw39we {
  stop-color: var(--svg-color--8d6b54, #8D6B54);
}

.q62993b5f {
  stop-color: var(--svg-color--935a6e, #935A6E);
}

.qa8ylsbmy {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M20.798 2.67c-2.137 2.178-4.641 5.148-5.516 8.633l-.223 2.765h5.031c1.032-1.823 2.813-5.32 4.575-7.305s.555-3.777-.067-4.308a2.68 2.68 0 0 0-3.8.215");
}

.qf0fwq23q {
  stop-color: var(--svg-color--6c4538, #6C4538);
}

.qq2xvsbus {
  stroke: var(--svg-color--cca58d, #CCA58D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.717 3.988c2.11 2.245 4.896 6.194 5.22 9.602c.345 3.617 0 5.966 0 7.36");
}

.rmqpg9b0t {
  stop-color: var(--svg-color--8c6f5b, #8C6F5B);
  stop-opacity: 0;
}

.s8scx1bpu {
  stop-color: var(--svg-color--261716, #261716);
  stop-opacity: 0;
}

.svdxfhbbg {
  stop-color: var(--svg-color--cfa590, #CFA590);
  stop-opacity: 0;
}

.t4jtfac7z {
  stop-color: var(--svg-color--8c5165, #8C5165);
}

.txlar6bix {
  stop-color: var(--svg-color--8c6f5b, #8C6F5B);
}

.u69ow0smy {
  stop-color: var(--svg-color--c9a385, #C9A385);
  stop-opacity: 0;
}

.urk3w6bnk {
  stop-color: var(--svg-color--956468, #956468);
}

.uzauj2_4e {
  stop-color: var(--svg-color--774e37, #774E37);
}

.v4ip-ttng {
  fill: var(--svg-color--b49275, #B49275);
  d: path("M10.32 10.673c0-1.646 1.272-2.98 2.84-2.98c1.569 0 2.84 1.334 2.84 2.98v2.743c0 1.646-1.271 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.vaqq6obaf {
  stop-color: var(--svg-color--90665f, #90665F);
  stop-opacity: 0;
}

.vvx90yqyz {
  d: path("M5.81 11.424c0-1.43 1.249-2.59 2.79-2.59c1.542 0 2.791 1.16 2.791 2.59v2.383c0 1.43-1.25 2.59-2.79 2.59c-1.542 0-2.792-1.16-2.792-2.59z");
}

.w92m0ew7o {
  fill: var(--svg-color--6e4044, #6E4044);
  d: path("M6.362 11.915c0-1.357 1.154-2.456 2.579-2.456c1.424 0 2.579 1.1 2.579 2.456v2.26c0 1.356-1.155 2.455-2.58 2.455c-1.424 0-2.578-1.1-2.578-2.456z");
}

.whu-6q9-s {
  stroke: var(--svg-color--d0a98d, #D0A98D);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M23.567 4.419c-.928 1.151-1.946 2.619-3.246 4.415");
}

.wlc_0fj7m {
  d: path("m5.997 20.578l-.188-5.114v-1.556h.002c.06 1.382 1.286 2.485 2.79 2.485c.966 0 1.818-.456 2.319-1.15c.52.7 1.33 1.15 2.24 1.15c1.408 0 2.576-1.075 2.8-2.485h4.318c.01-.843-1.844-4.115-4.254-7.32c-1.422-1.89-.62-3.565.516-4.305c1.476-.96 3.218-.25 3.945.899c0 0 5.637 5.93 5.637 13.304c.127 4.64.031 5.398-1.22 7.86c-1.814 3.575-5.716 5.357-9.247 5.357c-5.813 0-9.47-4.138-9.658-9.125");
}

.xjq13x_cu {
  d: path("M10.32 10.673c0-1.646 1.272-2.98 2.84-2.98c1.569 0 2.84 1.334 2.84 2.98v2.743c0 1.646-1.271 2.98-2.84 2.98s-2.84-1.334-2.84-2.98z");
}

.xxc65wsdn {
  stop-color: var(--svg-color--c9a385, #C9A385);
}

.ykv0gywid {
  d: path("M17.813 13.24a2.984 2.984 0 0 0 0 5.969h1.59a1 1 0 0 1 .788.385l2.045 2.621c1.17 1.501 3.577.674 3.577-1.23V19.24a6 6 0 0 0-5.212-5.949a3 3 0 0 0-.554-.051z");
}

.yugveyzaq {
  d: path("M20.112 13.24c1.027.112 3.179.378 4.779 2.76c.887-7.739-4.406-12.815-4.406-12.815c-.727-1.148-2.469-1.859-3.945-.898c-1.136.739-1.938 2.414-.516 4.305c1.979 2.63 3.583 5.307 4.088 6.648");
}

.z0vpmcszf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.722 15.76h.614c2.03 0 4.2.588 4.724 2.548c.1.372.175.788.214 1.25");
}

.z43dy1qxy {
  stop-color: var(--svg-color--b5877e, #B5877E);
  stop-opacity: 0;
}

.z6zvxkbqp {
  stop-color: var(--svg-color--8f6361, #8F6361);
  stop-opacity: 0;
}

.zetiuj7eb {
  stop-color: var(--svg-color--5c342e, #5C342E);
  stop-opacity: 0;
}

</style>
