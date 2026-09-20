<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVGPxb7AA7i)" class="pw41g3z5i"/><path class="vhg38y6ln"/><path fill="url(#SVGYmZmgvDZ)" class="cfrqhnr1u"/><path fill="url(#SVGrR6cnUDJ)" class="hl9kctbhc"/><path class="bt_0o9yrh"/><path fill="url(#SVGdFU9LDwl)" class="wjww--00q"/><path fill="url(#SVGDbacXcWN)" class="ulry-2h2n"/><path fill="url(#SVGNy5qLKzs)" class="yyle35dlh"/><path class="r6xo1fbms"/><path class="y6ce6lblb"/><path class="j-x830bkb"/><path class="iekw7251c"/><path fill="url(#SVGpj6LIhWo)" class="jqcauxbmv"/><path fill="url(#SVGXhVhacnH)" class="tg5ivtb4c"/><path fill="url(#SVGZZ12ycmI)" class="spfhpu5_v"/><path class="tk1d89bac"/><path fill="url(#SVGf19NwdsZ)" class="x5f2q1uds"/><path fill="url(#SVG4p8NIdIu)" class="e4__1cbpx"/><path fill="url(#SVGF565IFkn)" class="gue_p40cx"/><path class="ruf1xs9zj"/><path class="l3dp5lyon"/><path fill="url(#SVGSspledSo)" class="kts2j_b6x"/><path class="b4jeaqacl"/><path class="xbg18s3ct"/><path class="r1i5tvb9j"/><path fill="url(#SVGy6ncecTG)" class="wcaj6bctv"/><path fill="url(#SVGlcfaSdBH)" class="wtrabsuuu"/><path class="gg-39_bws"/><path fill="url(#SVGNfqP0coo)" class="ue-p5cb9c"/><path class="l75uiytpo"/><path class="lmqytpb3z"/><path class="uuotey6lk"/><path class="z36bx1cue"/><path fill="url(#SVGgn9gcdrk)" class="j_94b4bxb"/><path fill="url(#SVGX5jCLe1x)" class="xbnseabqp"/><path class="rkhhzbcdi"/><path class="ytjgusgrx"/><path fill="url(#SVGUhgP9bzl)" class="p203hi2jc"/><path fill="url(#SVGYCM4IeAy)" class="t0twtdbkw"/><path fill="url(#SVGlfSLZddi)" class="lcdeuubxy"/><path class="j7ql-4t6d"/><path fill="url(#SVGb2Acjbbq)" class="jcr8hxb2d"/><path fill="url(#SVGn7UxOcAy)" class="ols6jcuog"/><path fill="url(#SVGMkQngdOW)" class="fp5j4zxfh"/><path fill="url(#SVGj7uOyeVj)" class="y9cop3bsl"/></g><defs><linearGradient id="SVGPxb7AA7i" x1="7.516" x2="20.495" y1="5.156" y2="17.088" gradientUnits="userSpaceOnUse"><stop offset=".2" class="hgv1qkzmi"/><stop offset="1" class="ftp44ubhv"/></linearGradient><linearGradient id="SVGYmZmgvDZ" x1="12" x2="12" y1="4.767" y2="19.252" gradientUnits="userSpaceOnUse"><stop class="lkwk-enmf"/><stop offset="1" class="gs1rgacns"/></linearGradient><linearGradient id="SVGrR6cnUDJ" x1="4.356" x2="20" y1="8.606" y2="8.55" gradientUnits="userSpaceOnUse"><stop offset=".17" class="qe5p48b4r"/><stop offset=".32" class="bslchcr3i"/><stop offset=".58" class="t-p_icbpw"/><stop offset=".78" class="kym5k3bvu"/></linearGradient><linearGradient id="SVGdFU9LDwl" x1="12" x2="12" y1="4.75" y2="19.252" gradientUnits="userSpaceOnUse"><stop class="pcjcgzvra"/><stop offset="1" class="hi9fl4jvk"/></linearGradient><linearGradient id="SVGDbacXcWN" x1="11.977" x2="11.977" y1="4.756" y2="19.289" gradientUnits="userSpaceOnUse"><stop class="c2-sg9bnd"/><stop offset="1" class="l1t7q5i5a"/></linearGradient><linearGradient id="SVGNy5qLKzs" x1="12.05" x2="12.05" y1="4.749" y2="19.251" gradientUnits="userSpaceOnUse"><stop class="c2-sg9bnd"/><stop offset="1" class="l1t7q5i5a"/></linearGradient><linearGradient id="SVGpj6LIhWo" x1="11.968" x2="11.968" y1="4.75" y2="19.264" gradientUnits="userSpaceOnUse"><stop class="k3tceigbx"/><stop offset="1" class="yoxy9n3zl"/></linearGradient><linearGradient id="SVGXhVhacnH" x1="18.747" x2="2.956" y1="4.735" y2="18.066" gradientUnits="userSpaceOnUse"><stop offset=".41" class="eqgdkenmw"/><stop offset=".87" class="b8cyp9bra"/></linearGradient><linearGradient id="SVGZZ12ycmI" x1="6.319" x2="6.8" y1="4.456" y2="19.416" gradientUnits="userSpaceOnUse"><stop offset=".11" class="uquvcvmjj"/><stop offset=".41" class="omx0adcqb"/></linearGradient><linearGradient id="SVGf19NwdsZ" x1="12.03" x2="12.03" y1="4.761" y2="19.252" gradientUnits="userSpaceOnUse"><stop class="k3tceigbx"/><stop offset="1" class="yoxy9n3zl"/></linearGradient><linearGradient id="SVG4p8NIdIu" x1="17.645" x2="17.163" y1="4.485" y2="19.422" gradientUnits="userSpaceOnUse"><stop offset=".11" class="uquvcvmjj"/><stop offset=".41" class="omx0adcqb"/></linearGradient><linearGradient id="SVGF565IFkn" x1="13.17" x2="20.509" y1="6.654" y2="12.373" gradientUnits="userSpaceOnUse"><stop offset=".08" class="vc--wpv5i"/><stop offset=".28" class="o0flgdczd"/><stop offset=".93" class="xee_n81oa"/></linearGradient><linearGradient id="SVGSspledSo" x1="11.995" x2="11.995" y1="4.742" y2="19.252" gradientUnits="userSpaceOnUse"><stop class="zai5mibkl"/><stop offset=".75" class="av1d7xmof"/><stop offset=".84" class="l2kx9pb4e"/></linearGradient><linearGradient id="SVGy6ncecTG" x1="11.998" x2="11.998" y1="4.344" y2="19.245" gradientUnits="userSpaceOnUse"><stop class="muxgjn60t"/><stop offset=".23" class="ebwyr9bvz"/></linearGradient><linearGradient id="SVGlcfaSdBH" x1="12" x2="14.205" y1="11.989" y2="20.715" gradientUnits="userSpaceOnUse"><stop class="c2-sg9bnd"/><stop offset="1" class="l1t7q5i5a"/></linearGradient><linearGradient id="SVGNfqP0coo" x1="11.989" x2="11.989" y1="4.744" y2="19.294" gradientUnits="userSpaceOnUse"><stop class="ms3d2-rzr"/><stop offset=".63" class="uxmd3ybgg"/></linearGradient><linearGradient id="SVGgn9gcdrk" x1="17.7" x2="4" y1="11.974" y2="11.974" gradientUnits="userSpaceOnUse"><stop class="dt8lqd3pr"/><stop offset=".26" class="ddxe9tokv"/></linearGradient><linearGradient id="SVGX5jCLe1x" x1="6.266" x2="20" y1="11.974" y2="11.974" gradientUnits="userSpaceOnUse"><stop class="dt8lqd3pr"/><stop offset=".26" class="ddxe9tokv"/></linearGradient><linearGradient id="SVGUhgP9bzl" x1="17.691" x2="3.999" y1="12.001" y2="12.001" gradientUnits="userSpaceOnUse"><stop offset=".09" class="dt8lqd3pr"/><stop offset=".6" class="k_83deb1t"/></linearGradient><linearGradient id="SVGYCM4IeAy" x1="12.038" x2="12.038" y1="4.749" y2="19.251" gradientUnits="userSpaceOnUse"><stop class="gu40mjxob"/><stop offset=".48" class="w6e4oy_ul"/></linearGradient><linearGradient id="SVGlfSLZddi" x1="6.365" x2="20" y1="12.023" y2="12.023" gradientUnits="userSpaceOnUse"><stop class="dt8lqd3pr"/><stop offset=".81" class="k_83deb1t"/></linearGradient><linearGradient id="SVGb2Acjbbq" x1="12.043" x2="12.043" y1="4.705" y2="19.251" gradientUnits="userSpaceOnUse"><stop class="gu40mjxob"/><stop offset=".48" class="w6e4oy_ul"/></linearGradient><linearGradient id="SVGn7UxOcAy" x1="12" x2="12" y1="4.705" y2="19.25" gradientUnits="userSpaceOnUse"><stop class="gu40mjxob"/><stop offset=".71" class="w6e4oy_ul"/></linearGradient><linearGradient id="SVGMkQngdOW" x1="12" x2="12" y1="4.75" y2="19.252" gradientUnits="userSpaceOnUse"><stop class="gu40mjxob"/><stop offset="1" class="w6e4oy_ul"/></linearGradient><linearGradient id="SVGj7uOyeVj" x1="19.575" x2="19.575" y1="16.169" y2="18.084" gradientUnits="userSpaceOnUse"><stop class="gu40mjxob"/><stop offset="1" class="w6e4oy_ul"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:0xgas-background" /></template>
<style>
.av1d7xmof {
  stop-color: var(--svg-color--f9fefb, #f9fefb);
}

.b4jeaqacl {
  fill: var(--svg-color--0c0116, #0c0116);
  d: path("M19.985 15.464q-.008-.015-.015 0c-.025.265-.145.475-.275.705c-.395.685-1.535.955-2.29 1.035l-9.58.03c-1.34.005-3.27-.15-3.82-1.565c0 .325-.014 1.025.04 1.345l.016.22c-.005.64.26 1.05.6 1.55c.705-.21 1.52.8 2.19.35a.3.3 0 0 1 .14-.05c.36-.02.74 0 1.11.015c2.4.125 5.37-.01 7.734.015c.16.02.315.06.65.125c.58.02 1.715-.125 2.305-.375c.14-.06.23-.175.32-.285l.06-.07c.5-.6.71-1.59.81-2.4c.02-.205.03-.44 0-.645z");
}

.b8cyp9bra {
  stop-color: var(--svg-color--451066, #451066);
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bslchcr3i {
  stop-color: var(--svg-color--edf1ee, #edf1ee);
}

.bt_0o9yrh {
  fill: var(--svg-color--080210, #080210);
  d: path("m14.015 8.194l.13.02l.24.08a.02.02 0 0 1 .01.01a.02.02 0 0 1 0 .015l-.005.005l-.1.075a1.4 1.4 0 0 1-.26.01q-.104-.009-.125-.1q-.024-.114.11-.115");
}

.c2-sg9bnd {
  stop-color: var(--svg-color--26272a, #26272a);
}

.cfrqhnr1u {
  d: path("M9.56 7.016c.41-.015.825-.02 1.24-.005h2.185c.59 0 1.19-.035 1.78.015c.1.005.2.03.31.07q.285.114.555.265c.11.06.24.14.255.26q.061.414.07.835c0 .085-.655.12-.75.17L15.14 7.9c-.08-.025-.175-.07-.25-.085c-.1-.015-.785-.08-.875-.195c-.08-.1-.1-.25-.15-.37h-3.8c-.055.01-.095.245-.105.3a.06.06 0 0 1-.05.045l-1.105.31c-.065.215-.03.45-.05.665c-.245 0-.485-.065-.73-.075c0-.32.015-.605.06-.865c.04-.23.69-.485.89-.55a1.8 1.8 0 0 1 .585-.065m4.7.185c-.025.1-.015.265.11.295c.115.03.215 0 .3-.075c.05-.045.04-.1.015-.15a.4.4 0 0 0-.43-.07zm-5.015.05c-.1.265.23.36.39.175c.21-.255-.32-.375-.39-.18z");
}

.ddxe9tokv {
  stop-color: var(--svg-color--6f5874, #6f5874);
}

.dt8lqd3pr {
  stop-color: var(--svg-color--f2d9fd, #f2d9fd);
}

.e4__1cbpx {
  d: path("M7.65 10.016c-.05.375-.51 3.81-.554 3.83c-.22.095-.395.28-.635.3c-.09.01-.09.01-.13-.07v-.01c.165-1.13.305-2.28.56-3.4c.01-.05.05-.13.1-.25c.075-.065.505-.475.665-.4z");
}

.ebwyr9bvz {
  stop-color: var(--svg-color--3a3b3d, #3a3b3d);
}

.eqgdkenmw {
  stop-color: var(--svg-color--fbf5fa, #fbf5fa);
}

.fp5j4zxfh {
  d: path("m4.456 16.635l-.29-.4l.07 1.44l.22.375z");
}

.ft5dv1b6b {
  fill: none;
}

.ftp44ubhv {
  stop-color: var(--svg-color--89888d, #89888d);
}

.gg-39_bws {
  fill: var(--svg-color--211427, #211427);
  d: path("M10.075 8.25c.015.015.03.035.03.055a.23.23 0 0 1-.01.13l-.02.02c-.05.03-.1.05-.16.05a.3.3 0 0 1-.16-.035a.5.5 0 0 1-.165-.15a.035.035 0 0 1 .007-.043l.013-.007c.105-.03.37-.085.465-.02");
}

.gs1rgacns {
  stop-color: var(--svg-color--6d7371, #6d7371);
}

.gu40mjxob {
  stop-color: var(--svg-color--fbebfa, #fbebfa);
}

.gue_p40cx {
  d: path("m13.465 9.285l-.095.14a1 1 0 0 1-.13.18l-.185.16c-.01.13-.015.245 0 .345c.4.67 1.265 1.92 1.8 2.4c-.03-.12-.035-.235-.04-.275c-.015-.32-.09-.65-.13-.97l.01-.205v-.01c.01-.01.025-.005.03.005l.225 1.365c.02.135.045.235.065.3c.02.08.05.15.09.2c.08.105.175.19.275.28l.13.11c-.03.05-.07.1-.12.135a.37.37 0 0 1-.255.085l-2.18.02h-.64l-1.99-.015c-.42 0-.915 0-1.48-.015c-.17-.005-.285-.1-.375-.215l.15-.145c.125-.1.275-.23.31-.4a.8.8 0 0 1 .16-.34c.005-.01.11-.215.125-.125q.006.054-.01.1c-.16.39-.44.95.26 1h.415q2.754-.015 3.91 0c.345.01.7.04 1.025-.08a.18.18 0 0 0 .135-.185c0-.21-.12-.515-.285-.675c-.215-.215-.425-.44-.635-.665c-.3-.325-.59-.65-.93-.925a3.7 3.7 0 0 1-.735-.75c.285-.345.75-.56 1.1-.83");
}

.hgv1qkzmi {
  stop-color: var(--svg-color--feffff, #feffff);
}

.hi9fl4jvk {
  stop-color: var(--svg-color--84619a, #84619a);
}

.hl9kctbhc {
  d: path("M14.29 7.885c.217.101.451.159.69.17c.015.155.135.64-.06.745l-.325.235l-1.525 1.14a.2.2 0 0 1-.02-.065c-.01-.1-.005-.215.005-.35l.185-.155c.09-.09.14-.215.225-.32q.279-.217.505-.48c.02.005.015.015 0 0c-.2-.05-.395-.15-.575-.145c-.26.42-.79.765-1.195 1.03l-.175.125c-.05.055-.105.015-.15-.025c-.405-.33-.84-.62-1.22-.98l-.02-.08c-.015-.07-.15-.045-.2-.045q-.24.053-.465.045q.06.114.21.25c.03.03.31.35.365.45q.151.292.34.57c.05.085.06.15 0 .235q-.015-.029-.06-.05c-.65-.42-1.3-1.01-1.86-1.475l.015-.585c.265-.085.525-.155.795-.225c.05-.015.09-.025.15.02c.1.09.2.175.31.25l.885.67l.89.665c.555-.415 1.695-1.36 2.28-1.62m-.385.425q-.024-.114.11-.115l.13.02c.035.01.27.05.25.1l-.005.01c-.03.025-.08.08-.115.08q-.099.015-.25 0c-.065 0-.105-.035-.12-.095");
}

.iekw7251c {
  fill: var(--svg-color--030109, #030109);
  d: path("m15.99 11.625l.075.45c0 .085 0 .165.015.25c.04.245.065.5.1.73l.04.14c.055.245.12.485.185.725a.2.2 0 0 1 0 .115a.4.4 0 0 1-.075.115q-.024-.015-.01-.06a.03.03 0 0 0-.005-.025a3.5 3.5 0 0 1-.375-.34q-.196-.241-.43-.415l-.115-.1c.135.015.24-.005.325-.075l.01-.015l-.005-.02a.5.5 0 0 0-.12-.115l-.125-.09a2.4 2.4 0 0 1-.385-.41q-.036-.051.025-.05c.01 0 .02.005.04.03q.315.265.62.54c.06.05.14.075.135.175q-.002.143.01.285l.015.02a.025.025 0 0 0 .035 0l.005-.015q.021-.414-.025-.82l-.055-.5q-.021-.375-.005-.75c0-.025.005-.035.02-.04c.01 0 .02.005.02.015z");
}

.j_94b4bxb {
  d: path("M10.496 17.565h1.564v1.385h-1.564z");
}

.j-x830bkb {
  fill: var(--svg-color--4b4450, #4b4450);
  d: path("M12.385 10.73a1.1 1.1 0 0 0-.38-.25c.08.1.075.195-.015.275c-.05.045-.195.135-.335.285l-.075.085c.335-.22.39-.23.7.03c.45.375.915.72 1.345 1.12c.16.01.33-.03.495-.015q.105.009.15-.05q-.3-.285-.63-.525c-.43-.3-.8-.69-1.25-.95z");
}

.j7ql-4t6d {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("m5.905 17.374l-.75-.25l.17 1.37l.745.295z");
}

.jcr8hxb2d {
  d: path("m5.905 17.374l-.75-.25l.17 1.37l.745.295z");
}

.jqcauxbmv {
  d: path("M15.98 10.365c-.155 1.055.05 2.055 0 3.1c0 .04-.535-.51-.615-.58c-.01-.885-.13-2.03-.13-2.905l.75.385z");
}

.k_83deb1t {
  stop-color: var(--svg-color--a27daa, #a27daa);
}

.k3tceigbx {
  stop-color: var(--svg-color--d8a6e4, #d8a6e4);
}

.kts2j_b6x {
  d: path("M15.95 10.716a2 2 0 0 0-.055-.165c-.02 0-.05-.01-.055.015v.015c.06.23.1.45.11.67l.04.375c.125.77.215 1.55.415 2.3c.01.04.01.08 0 .11c-.14.33-.6.46-.92.465c-.355.005-.71.01-1.065.005c-1.88-.01-3.75-.015-5.63-.015c-.255 0-.44-.01-.63-.085a1.5 1.5 0 0 1-.505-.35c-.05-.02-.07-.045-.05-.1l.05-.25c-.02-.05-.06 0-.08.02c-.065.665-.705 1.095-1.15 1.54a.06.06 0 0 0 0 .085l.23.21q.119.076.26.1l.05-.105a1.45 1.45 0 0 0 .44-.815q.015-.075.18-.06c2.745-.14 5.525-.015 8.27-.02l.65.01l.2-.01c.02.275.2.845.47.995c.01 0 .005.015-.01.03q.338-.098.585-.315l-.295-.27c-.29-.38-.44-.525-.77-.825a.56.56 0 0 1-.175-.36c-.18-1.055-.3-2.16-.56-3.2");
}

.kym5k3bvu {
  stop-color: var(--svg-color--626260, #626260);
}

.l1t7q5i5a {
  stop-color: var(--svg-color--82529c, #82529c);
}

.l2kx9pb4e {
  stop-color: var(--svg-color--97729e, #97729e);
}

.l3dp5lyon {
  fill: var(--svg-color--7a4b90, #7a4b90);
  d: path("M8.47 13.305c.035.05.045.065.03.055c.045.085.055.16.04.22c-.055.225-.155.69-.38.825a1.5 1.5 0 0 1-.505-.35zm7.04.005c.265.2.685.535.865.815c-.17.17-.29.35-.59.35a.3.3 0 0 0-.025-.14a4 4 0 0 1-.37-.89q.075-.053.12-.135");
}

.l75uiytpo {
  fill: var(--svg-color--f2bfed, #f2bfed);
  d: path("M13.5 12.25c.04.005.076.025.11.05c.016.015.006.045-.02.05l-3.25.01c-.014 0-.034-.064-.024-.08a.06.06 0 0 1 .05-.025z");
}

.lcdeuubxy {
  d: path("m7.206 17.533l-1.15-.1l.135 1.375l1.015.14z");
}

.lkwk-enmf {
  stop-color: var(--svg-color--a7a6ac, #a7a6ac);
}

.lmqytpb3z {
  fill: var(--svg-color--202025, #202025);
  d: path("M7.375 17.565h1.15v1.385h-1.15z");
}

.ms3d2-rzr {
  stop-color: var(--svg-color--020107, #020107);
}

.muxgjn60t {
  stop-color: var(--svg-color--a7a3a0, #a7a3a0);
}

.o0flgdczd {
  stop-color: var(--svg-color--80748d, #80748d);
}

.ols6jcuog {
  d: path("m5.01 17.104l-.45-.35l.08 1.48l.51.175l-.14-1.3z");
}

.omx0adcqb {
  stop-color: var(--svg-color--29282b, #29282b);
}

.p203hi2jc {
  d: path("m16.835 17.565l1.464-.135l-.13 1.225l-1.395.295z");
}

.pcjcgzvra {
  stop-color: var(--svg-color--48494f, #48494f);
}

.pw41g3z5i {
  d: path("M15.065 4.76c.12 0 .245.015.375.025c.72.05 2.515.185 2.78 1.05c.06.19.11.375.15.565c.65 2.75 1.05 5.45 1.615 8.824c0 .06.015.125.015.19c-.15 1.58-1.91 1.81-3.15 1.81l-3.725.025c-1.93-.04-2.7-.01-5.24 0c-1.24 0-3.31-.01-3.824-1.365a6.7 6.7 0 0 1-.05-1.28c.475-3.18 1.11-5.7 1.575-8.464c.02-.115.055-.235.115-.35c.02-.05.06-.095.1-.13c.93-.8 2.535-.89 3.69-.9h.2c1.79.05 3.584-.04 5.374 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qe5p48b4r {
  stop-color: var(--svg-color--80788b, #80788b);
}

.r1i5tvb9j {
  fill: var(--svg-color--d55be6, #d55be6);
  d: path("M15.95 5.96c-.035.01-.05-.07-.005-.075c.04 0 .08 0 .12.01q.297.075.575.205a2.1 2.1 0 0 1-.685-.14z");
}

.r6xo1fbms {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.4 9.244c.36.295.86.475 1.175.835c.08.095-.1.27-.18.34c-.525.48-1.07.92-1.55 1.455q-.226.255-.37.39c-.015.01-.03 0-.025-.02l.1-.135q.742-.885 1.335-1.875c.06-.08.05-.15 0-.235l-.485-.75z");
}

.rkhhzbcdi {
  fill: var(--svg-color--353438, #353438);
  d: path("M13.54 17.565h1.6v1.385h-1.6z");
}

.ruf1xs9zj {
  fill: var(--svg-color--761594, #761594);
  d: path("M14.666 12.455a1 1 0 0 1 .284.675q0 .134-.134.185c.024-.03.03-.055.01-.065a.49.49 0 0 1-.27-.395c-.015-.125.065-.28.11-.4");
}

.spfhpu5_v {
  d: path("M8.9 9.79c-.04.176-.16.31-.2.48c-.14.65-.09 1.376-.07 2.036c0 .1-.05.185-.125.25c-.115.1-.22.195-.325.3c-.08.075-.285.19-.55.825c-.005 0-.015 0-.025.01l-.03.035c.07-1.015.17-2.16.45-3.15a.42.42 0 0 1 .2-.205c.395-.24.525-.415.69-.825q.014.129-.01.25z");
}

.t-p_icbpw {
  stop-color: var(--svg-color--f9fff9, #f9fff9);
}

.t0twtdbkw {
  d: path("m18.405 17.344l.93-.425l-.205 1.285l-.83.41z");
}

.tg5ivtb4c {
  d: path("M11.99 10.75q.135-.115.015-.266a.12.12 0 0 0-.1.005c-.15.09-.295.185-.43.3c-.54.445-1.095.925-1 .86l-.22.165c.075.09.21.18.33.18c.475-.415.94-.82 1.405-1.24z");
}

.tk1d89bac {
  fill: var(--svg-color--500770, #500770);
  d: path("m16.585 11.56l.025.105c.05.64.135 1.28.195 1.92c.005.07 0 .13-.005.17c-.085.02-.3.05-.29.16l-.345-2.025l-.01-.13c.11.225.45-.02.43-.2");
}

.ue-p5cb9c {
  d: path("M13.885 8.055c-.43-.105-.855-.29-1.3-.255c-.41.03-.825.005-1.23.01c-.46.005-.95.29-1.205.3l1.855 1.4c.665-.435 1.26-.96 1.88-1.455");
}

.ulry-2h2n {
  d: path("M15.95 8.58c-.06-.085-.625-.045-.65.07c-.04.23.084 1.295.25 1.3c.064.005.645 0 .65-.09c-.085-.28-.06-1.025-.25-1.28");
}

.uquvcvmjj {
  stop-color: var(--svg-color--edcff5, #edcff5);
}

.uuotey6lk {
  fill: var(--svg-color--333237, #333237);
  d: path("M8.64 17.565h1.74v1.385H8.64z");
}

.uxmd3ybgg {
  stop-color: var(--svg-color--670680, #670680);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vhg38y6ln {
  fill: var(--svg-color--080210, #080210);
  d: path("m15.01 5.48l-1.15-.004l-4.665.01c-.25 0-.42.01-.52.03c-.375.065-.695.305-1.065.4c-.28.075-.505.135-.57.535q-.18 1.179-.32 2.364c-.23 1.91-.474 3.815-.72 5.72c0 .13-.02.27.026.4c.35.425.614.6.89.73c.16.075.304.12.45.14c.33.05.664.065 1.044.065c2.195.025 3.955.025 5.93.025c.71-.005 1.42.02 2.125-.045c.425-.035 1.38-.43 1.565-.865c.1-.235.03-.5-.02-.74a59 59 0 0 1-.79-5.225l-.3-2.394q-.03-.19-.065-.38c-.09-.5-1.31-.76-1.845-.765");
}

.w6e4oy_ul {
  stop-color: var(--svg-color--dc69ef, #dc69ef);
}

.wcaj6bctv {
  d: path("M16.61 6.81c.175.22.37.85.21 1.15q-.031.051-.115.05c-.2-.02-.435-.01-.635 0l-.045-.73a.1.1 0 0 0-.05-.08a7 7 0 0 1-.365-.21c-.175-.105-.185-.25-.2-.42c0-.025-.005 0-.01-.015c0-.045-.015-.065-.035-.075c-.065-.02-.185-.01-.255-.015l-1.03-.005q-1.949.016-3.89-.005c-.51.01-1.015.01-1.525-.01c-.025 0-.09.015-.1.05v.02c-.074.325-.144.58-.52.675c-.064.02-.094.04-.104.11q-.067.33-.105.69c0 .03-.02.05-.05.045l-.61-.05c-.085 0-.06-.17-.055-.215c.015-.2.045-.4.075-.6c.125-.71.87-.88 1.66-.92h6.384c.475 0 1.075.2 1.37.56");
}

.wjww--00q {
  d: path("M16.175 8.14c.03.24.18 1.18.25 1.455c.175.025.455 0 .57.025l-.165-1.615");
}

.wtrabsuuu {
  d: path("M7.75 8.07c-.15-.03-.55-.05-.624-.04c-.145.5-.2 1.035-.23 1.55c.11.045.55.075.664.075c.07-.15.195-1.39.195-1.585z");
}

.x5f2q1uds {
  d: path("M16.28 9.96c.495 1.205.215 2.6.56 3.83c.07.03.565.175.765.225c-.15-1.065-.185-2.66-.665-3.655c-.07-.06-.5-.47-.66-.4");
}

.xbg18s3ct {
  fill: var(--svg-color--e788ef, #e788ef);
  d: path("M7.576 6.085c-.04 0-.075 0-.1-.02c.13-.075.4-.225.52-.15c.02.01.02.045 0 .05q-.195.098-.42.12");
}

.xbnseabqp {
  d: path("M13.365 17.565H12.2v1.385h1.165z");
}

.xee_n81oa {
  stop-color: var(--svg-color--fae7f9, #fae7f9);
}

.y6ce6lblb {
  fill: var(--svg-color--b364b4, #b364b4);
  d: path("M9.45 12.246v.005c0 .005 0 .01.01.01h.016c-.1.1-.21.2-.17.32c.03.085.1.14.095.26a7 7 0 0 1-.18.475c-.14.11-.205.06-.305-.3c-.005-.04.025-.09.045-.125c.085-.175.18-.34.245-.5a.2.2 0 0 0 .01-.1c-.01 0-.045-.015-.06 0c.055-.42.09-.84.145-1.26c.01-.115.025-.245.025-.36c.015.41.005.815-.025 1.225c-.01.12 0 .325 0 .485c0-.005-.015.01 0 0l.15-.14z");
}

.y9cop3bsl {
  d: path("m19.515 16.81l.385-.64l-.31 1.35l-.335.564z");
}

.yoxy9n3zl {
  stop-color: var(--svg-color--59305d, #59305d);
}

.ytjgusgrx {
  fill: var(--svg-color--222224, #222224);
  d: path("M15.3 17.565h1.375l-.165 1.385H15.3z");
}

.yyle35dlh {
  d: path("M8.026 8.5c.075.114-.06.97-.095 1.22q.27-.024.54.05c.18-.846.265-1 .265-1.196c-.19-.06-.47-.07-.71-.08z");
}

.z36bx1cue {
  fill: var(--svg-color--d9d9d9, #d9d9d9);
  d: path("M10.496 17.565h1.564v1.385h-1.564z");
}

.zai5mibkl {
  stop-color: var(--svg-color--b594b5, #b594b5);
}

</style>
