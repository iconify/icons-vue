<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(.9 .72)scale(.94379)"><defs><linearGradient id="SVG73m99b7z" x1="102" x2="105" y1="156" y2="156" gradientTransform="matrix(-.864 0 0 .864 115 -122)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zhfakqbtq"/><stop offset="1" class="kdm06vb1s"/></linearGradient><linearGradient id="SVGgQ2q5bcA" x1="97.2" x2="94.9" y1="146" y2="150" gradientTransform="matrix(.827 .25 -.25 .827 -16.3 -121)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGuktrkdnU" x1="97.2" x2="94.9" y1="146" y2="150" gradientTransform="matrix(.827 .25 -.25 .827 -16.3 -121)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="co03y-bdw"/></linearGradient><linearGradient id="SVG5Aa1pJyG" x1="96.9" x2="94.6" y1="147" y2="151" gradientTransform="matrix(.827 .25 -.25 .827 -15.9 -122)" href="#SVGgQ2q5bcA"/><linearGradient id="SVGLSFQAccQ" x1="96.9" x2="94.6" y1="147" y2="151" gradientTransform="matrix(.827 .25 -.25 .827 -15.9 -122)" href="#SVGuktrkdnU"/><linearGradient id="SVGrMHBOdTV" x1="96.6" x2="94.3" y1="148" y2="152" gradientTransform="matrix(.827 .25 -.25 .827 -15.4 -124)" href="#SVGgQ2q5bcA"/><linearGradient id="SVGU1pNwc6h" x1="96.6" x2="94.3" y1="147" y2="152" gradientTransform="matrix(.827 .25 -.25 .827 -15.4 -124)" href="#SVGuktrkdnU"/><linearGradient id="SVGiSaOkdSu" x1="96.3" x2="94" y1="148" y2="153" gradientTransform="matrix(.827 .25 -.25 .827 -15 -125)" href="#SVGgQ2q5bcA"/><linearGradient id="SVG5ItmAgFY" x1="96.3" x2="94" y1="148" y2="152" gradientTransform="matrix(.827 .25 -.25 .827 -15 -125)" href="#SVGuktrkdnU"/><linearGradient id="SVGamZK0b0w" x1="96" x2="93.7" y1="149" y2="153" gradientTransform="matrix(.827 .25 -.25 .827 -14.6 -127)" href="#SVGgQ2q5bcA"/><linearGradient id="SVGM4qFHCpZ" x1="96" x2="93.7" y1="149" y2="153" gradientTransform="matrix(.827 .25 -.25 .827 -14.6 -127)" href="#SVGuktrkdnU"/><linearGradient id="SVGLvXkjbCD" x1="-69.9" x2="-68.4" y1="5.01" y2="8.62" gradientTransform="matrix(.939 -.879 -.683 -.73 84.9 -29.9)" href="#SVG0mwgqd9n"/><linearGradient id="SVGIE2Q8cxh" x1="-26.7" x2="-25.3" y1="33.6" y2="38" gradientTransform="matrix(1.13 .613 .477 -.879 21.4 69.8)" href="#SVG0mwgqd9n"/><linearGradient id="SVGYfo1eehV" x1="-67.4" x2="-67.5" y1="8.4" y2="5.62" gradientTransform="matrix(.918 -.859 -.668 -.713 78 -32.8)" href="#SVG0mwgqd9n"/><linearGradient id="SVGtIg46cnZ" x1="-93" x2="-92.6" y1="95.8" y2="98.6" gradientTransform="matrix(-1.28 -.126 -.098 .995 -97.1 -90.8)" href="#SVG0mwgqd9n"/><radialGradient id="SVGxq0OAd4z" cx="7.98" cy="19" r="16.6" gradientTransform="matrix(.883 0 0 -.883 1.99 33.7)" gradientUnits="userSpaceOnUse"><stop offset="0" class="n45-qabho"/><stop offset=".15" class="n45-qabho"/><stop offset=".75" class="ysbj1jbfw"/><stop offset="1" class="kjsw3bzhe"/></radialGradient><radialGradient id="SVGeu74vcwe" cx="6.52" cy="21" r="24.1" gradientTransform="matrix(.883 0 0 -.883 1.99 33.7)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="w93_x0byt"/></radialGradient><radialGradient id="SVG0mwgqd9n" cx="-34.8" cy="8.18" r="3.72" gradientTransform="rotate(143.75 -13.6 17.53)scale(.883)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="SVG7bvkFdOm" cx="-32.9" cy="32.7" r="3.72" gradientTransform="rotate(143.74 -8.59 41.03)scale(1.145)" href="#SVG0mwgqd9n"/><radialGradient id="SVGU7VbIoOw" cx="-38.8" cy="12.7" r="3.72" gradientTransform="rotate(143.75 -16.04 23.31)scale(.883)" href="#SVG0mwgqd9n"/><radialGradient id="SVGQiLijcZU" cx="-30.8" cy="15.4" r="3.72" gradientTransform="matrix(-.768 .564 -.563 -.768 -2.96 44.7)" href="#SVG0mwgqd9n"/></defs><path class="nphsxqjiq"/><path class="g12xvpijq"/><path class="p8ac30ixk"/><path class="sf5xe9i2m"/><path class="qfgu9_lys"/><path class="b-moe-b7m"/><path fill="url(#SVG73m99b7z)" class="mm_me1xuu"/><path class="orcxgko1i"/><path class="b0_g9vbuz"/><path fill="url(#SVGgQ2q5bcA)" class="cw15tg-qf"/><path fill="url(#SVGuktrkdnU)" class="rf91v9b6c"/><path fill="url(#SVG5Aa1pJyG)" class="zin1ubb9n"/><path fill="url(#SVGLSFQAccQ)" class="fomx14beu"/><path fill="url(#SVGrMHBOdTV)" class="ktxs9eyes"/><path fill="url(#SVGU1pNwc6h)" class="vkw3fabci"/><path fill="url(#SVGiSaOkdSu)" class="cf_zjwvud"/><path fill="url(#SVG5ItmAgFY)" class="pcedytbzj"/><path fill="url(#SVGamZK0b0w)" class="ik8z1db9m"/><path fill="url(#SVGM4qFHCpZ)" class="nuqjlqzet"/><path fill="url(#SVGxq0OAd4z)" class="x_f8f8bgl"/><path class="w3h8jkb7h"/><path class="z6a4c1b2v"/><path class="s_odpubgz"/><path class="vh01ll2fg"/><path fill="url(#SVGeu74vcwe)" class="tcinaljvn"/><path fill="url(#SVG0mwgqd9n)" class="cqy2bxb5n"/><path class="yt16mbc6i"/><path fill="url(#SVG7bvkFdOm)" class="a3xyuv6ke"/><path class="y6f5i7mht"/><path fill="url(#SVGU7VbIoOw)" class="u3hwwvwjx"/><path class="g26w4kc7z"/><path fill="url(#SVGQiLijcZU)" class="n27p75-2z"/><path class="hlp1ycbuq"/><path fill="url(#SVGLvXkjbCD)" class="nzp78ndkp"/><path fill="url(#SVGIE2Q8cxh)" class="ltce37bth"/><path fill="url(#SVGYfo1eehV)" class="u00adqbwm"/><path fill="url(#SVGtIg46cnZ)" class="ozp67acuz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-host" /></template>
<style>
.a3xyuv6ke {
  d: path("M13.6 29.2a4.25 4.25 0 0 0 6.91-4.96l-.05-.07a4.25 4.25 0 0 0-6.86 5.03");
}

.b-moe-b7m {
  fill: var(--svg-color--00608b, #00608b);
  d: path("M14.7 7.48a3 3 0 0 1 .5.33zm5.66 22.3c.32.13.37-.17.37-.17a.4.4 0 0 0 .4.33a.7.7 0 0 1-.77-.16M10.7 4.74c-.3-.35.26-.63.26-.63c-.7.2-.7.64-.66.88c0-.23.12-.38.4-.24Z");
}

.b0_g9vbuz {
  fill: var(--svg-color--fff, #fff);
  d: path("m24.1 13.8l3-1.1l-.2-.1l-2.7 1v-.3l-.1-.2z");
  opacity: var(--svg-opacity--0-72, 0.72);
}

.cf_zjwvud {
  d: path("m29 22.3l-7.02 2.44l-.06.21l7.04-2.52z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.co03y-bdw {
  stop-color: var(--svg-color--6a6a6a, #6a6a6a);
}

.cqy2bxb5n {
  d: path("M3.66 17.6a3.28 3.28 0 0 0 5.35-3.79l-.06-.09a3.28 3.28 0 0 0-5.3 3.88z");
}

.cw15tg-qf {
  d: path("m29 24.9l-7.02 2.44l-.06.21l7.03-2.52z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.fomx14beu {
  d: path("m29.1 23.9l-7.05 2.44l-.06.21l7.05-2.54z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.g12xvpijq {
  fill: var(--svg-color--00608b, #00608b);
  d: path("m17.86 2.09l.06-.06c-.33.11-6.7 2-6.96 2.09c-.24.08-.57.37-.4.54s9.56 6.59 9.73 6.7a1.2 1.2 0 0 0 1 .05c.27-.05 7.54-2.44 7.92-2.55c.39-.16.28-.5 0-.66A863 863 0 0 0 18.8 2.04a2 2 0 0 0-.94.05");
}

.g26w4kc7z {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.95 22.8a1.01 1.01 0 1 0 1.63-1.2a1.01 1.01 0 1 0-1.63 1.2");
}

.hlp1ycbuq {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.1 16.2a1.09 1.09 0 0 0 1.77-1.28a1.09 1.09 0 0 0-1.78 1.27z");
}

.ik8z1db9m {
  d: path("m29 21.4l-7.02 2.44l-.06.21l7.03-2.52z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.kdm06vb1s {
  stop-color: var(--svg-color--c4ce00, #c4ce00);
}

.kjsw3bzhe {
  stop-color: var(--svg-color--36486c, #36486c);
}

.ktxs9eyes {
  d: path("m29 23.2l-7.02 2.44l-.07.22l7.03-2.52z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.ltce37bth {
  d: path("M16.5 27a16.4 16.4 0 0 1-7.44-2.2c-4.98-2.7-7.87-6.68-6.57-9.06c.63-1.16 2.15-1.73 4.3-1.6a17 17 0 0 1 6.88 2.17a17 17 0 0 1 5.57 4.58c1.28 1.73 1.64 3.32 1 4.48c-.6 1.09-1.95 1.63-3.73 1.63zM6.2 14.6c-1.67 0-2.85.49-3.34 1.4c-1.16 2.13 1.71 5.94 6.4 8.48s9.44 2.87 10.6.74c.55-1.01.2-2.43-.97-4.02a17 17 0 0 0-5.43-4.46a17 17 0 0 0-6.7-2.11q-.3-.03-.56-.03");
}

.mm_me1xuu {
  d: path("m26.9 12.3l-2.7 1v.3l2.7-1z");
}

.n27p75-2z {
  d: path("M9.14 17.6a3.54 3.54 0 0 0 5.73-4.16l-.02-.03a3.54 3.54 0 0 0-5.73 4.16z");
}

.n45-qabho {
  stop-color: var(--svg-color--d3e9ff, #d3e9ff);
}

.nphsxqjiq {
  fill: var(--svg-color--00608b, #00608b);
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-28px, 1.28px);
  d: path("M11 4.11a.75.75 0 0 0-.61.67v.05l.26 17.18a1 1 0 0 0 .22.44c.17.16 9.42 7.2 9.58 7.3l.06.06c.16.17.28.17.66.12h.12c.83-.23 8.04-3.11 8.04-3.11c.22-.11.27-.22.27-.5l.12-17.23a1.2 1.2 0 0 0-.39-.84c-.05-.05-.05-.1-.11-.1c-.33-.18-10.27-6-10.44-6.06a2 2 0 0 0-.94.06c-.33.1-6.56 1.9-6.84 1.95Zm9.8 25.59ZM11.17 4.94a4 4 0 0 1-.5-.34c.23.17 1.06.72 2 1.39q-.85-.65-1.44-1.06l-.38-.27z");
}

.nuqjlqzet {
  d: path("m29.1 21.2l-7.06 2.45l-.06.21l7.05-2.54z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.nzp78ndkp {
  d: path("M9.36 30.4a3 3 0 0 1-2.32-.87c-.9-.96-.96-2.59-.16-4.59a17 17 0 0 1 4.23-5.84c4.13-3.87 8.82-5.35 10.7-3.37c.9.97.96 2.6.16 4.6a17 17 0 0 1-4.23 5.83A17 17 0 0 1 11.63 30a7 7 0 0 1-2.24.4zm10.1-15.1c-2.15 0-5.26 1.52-8.05 4.13a17 17 0 0 0-4.12 5.69c-.73 1.83-.7 3.3.08 4.13s2.24.96 4.12.35a17 17 0 0 0 5.94-3.74a17 17 0 0 0 4.12-5.68c.74-1.83.71-3.3-.07-4.13a2.7 2.7 0 0 0-2.02-.75");
}

.orcxgko1i {
  d: path("m26.9 12.3l-2.7 1l-.1-.2l3-1v.6l-.2-.1z");
  opacity: var(--svg-opacity--0-22, 0.22);
}

.ozp67acuz {
  d: path("M13.2 24.9q-1.03 0-2.12-.1c-5.63-.56-9.84-3.1-9.58-5.8s4.89-4.4 10.5-3.84s9.84 3.1 9.57 5.8c-.23 2.35-3.77 3.92-8.4 3.92zM1.9 19.04c-.24 2.42 3.88 4.81 9.19 5.33s9.81-1.02 10.1-3.43s-3.88-4.8-9.19-5.33s-9.81 1.02-10 3.43z");
}

.p8ac30ixk {
  fill: var(--svg-color--00608b, #00608b);
  d: path("M29.5 26.32c0 .27-.06.38-.28.5c0 0-7.2 2.88-8.04 3.1a.35.35 0 0 1-.5-.33l-.11-17.51c0-.21.16-.34.44-.5c.28-.23 8.1-2.78 8.26-2.83c.23-.05.39.1.39.39Z");
}

.pcedytbzj {
  d: path("m29.1 22.1l-7.06 2.45l-.06.21l7.05-2.54z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.qfgu9_lys {
  fill: var(--svg-color--00608b, #00608b);
  d: path("M29.33 8.65c-.06 0-8.14 2.77-8.62 2.77c-.6 0-5.06-3.48-6.18-4.08a99 99 0 0 0 5.54 4.13c.33.22.51.42.51.7l.1.68l.06-.67c0-.27.16-.37.44-.49s7.15-2.5 8.15-2.82a.35.35 0 0 1 .33.27a1.2 1.2 0 0 0-.5-.94c.17.16.22.44.17.44Z");
}

.rf91v9b6c {
  d: path("m29.1 24.8l-7.06 2.45l-.06.21l7.05-2.54z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.s_odpubgz {
  fill: var(--svg-color--204a87, #204a87);
  fill-opacity: var(--svg-fill-opacity--0-71, 0.71);
  d: path("m14.15 15.45l-.07.48l.39-.08l.28-.28l-.25-.24l-.28-.63h-.2v.24l.13.16zM9 22.96l-.28-.56l-.52-.12l-.28-.75l-.7.08l-.6-.43l-.62.55v.09a2 2 0 0 1-.6-.17l-.13-.4v-.44l-.42.04l.1-.82H4.7l-.24.31l-.25.12l-.34-.2l-.04-.43l.07-.47l.53-.4h.4l.08-.24l.52.11l.38.48l.07-.8l.67-.54l.25-.6l.48-.2l.28-.4l.63-.11l.31-.46h-.94l.6-.28h.41l.6-.2l.06-.24l-.2-.2l-.25-.08l.07-.24l-.17-.35l-.42.16l.07-.32l-.5-.28l-.38.68l.04.24l-.38.15l-.25.52l-.1-.48l-.66-.27l-.1-.36l.87-.5l.39-.36l.03-.44l-.2-.12l-.29-.04l-.17.44l-.37.07a10 10 0 0 0-3.34 6.39a5 5 0 0 0 .33.56l.73.44l.73.2l.31.4l.5.35l.27-.04l.21.1v.06l-.28.75l-.2.32l.06.16l-.18.59l.63 1.14l.62.56l.28.4l-.03.81l.21.47l-.21.91s-.02 0 .01.09A4 4 0 0 0 8.1 29l.13-.1l-.07-.2l.28-.28l.1-.27l.45-.16l.35-.87l-.1-.24l.24-.35l.53-.12l.28-.64l-.07-.78l.41-.6l.07-.59q-.86-.42-1.7-.87M8.22 14l.35.24h.28v-.28l-.35-.16z");
}

.sf5xe9i2m {
  fill: var(--svg-color--00608b, #00608b);
  d: path("m20.4 29.81l.06.06c-.12-.17-9.44-7.28-9.6-7.44a.4.4 0 0 1-.23-.4L10.32 5c-.06-.17.06-.5.28-.33s9.64 6.7 9.8 6.81a.7.7 0 0 1 .28.56l.07 17.45c0 .32-.18.45-.35.34Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tcinaljvn {
  d: path("M12.1 30a9.23 9.23 0 1 1 9.23-9.23A9.23 9.23 0 0 1 12.1 30m0-18a8.74 8.74 0 1 0 8.74 8.74A8.75 8.75 0 0 0 12.1 12");
  opacity: var(--svg-opacity--0-4, 0.4);
}

.u00adqbwm {
  d: path("M7.22 28.6a3 3 0 0 1-2.27-.85c-.89-.94-.94-2.54-.16-4.49a17 17 0 0 1 4.14-5.7c4.04-3.79 8.63-5.24 10.4-3.3c1.81 1.94.07 6.42-3.98 10.2a17 17 0 0 1-5.97 3.75a7 7 0 0 1-2.2.4zm9.86-14.8c-2.1 0-5.13 1.49-7.86 4.04a16 16 0 0 0-4.02 5.55c-.72 1.78-.69 3.22.07 4.03s2.2.93 4.02.34a16 16 0 0 0 5.81-3.65c3.8-3.56 5.57-7.85 3.96-9.58a2.6 2.6 0 0 0-1.97-.72z");
}

.u3hwwvwjx {
  d: path("M3.12 24.2a3.28 3.28 0 1 0 5.29-3.88a3.28 3.28 0 0 0-5.29 3.88");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vh01ll2fg {
  fill: var(--svg-color--204a87, #204a87);
  fill-opacity: var(--svg-fill-opacity--0-71, 0.71);
  d: path("m7.32 13.68l-.18.43h.35l.18-.4l.45-.32l.35.12l.7.47l.35-.31l-.38-.16l-.18-.36l-.66-.08l-.04-.2l-.31.08l-.14.28l-.18-.36l-.06.16l.03.4zm1.25-.98l.18-.16l.35-.08a6 6 0 0 1 .73-.28l-.14-.24l-.45.07l-.21.21l-.35.05l-.32.15l-.15.07l-.09.13zm.59 3.75l.2-.32l-.3-.24z");
}

.vkw3fabci {
  d: path("m29.1 23l-7.06 2.45l-.06.21l7.05-2.54z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.w3h8jkb7h {
  fill: var(--svg-color--39396c, #39396c);
  d: path("M12.1 30.5a9.71 9.71 0 1 1 9.71-9.71a9.7 9.7 0 0 1-9.71 9.71m0-18.9a9.22 9.22 0 1 0 9.22 9.22a9.23 9.23 0 0 0-9.22-9.22");
}

.w93_x0byt {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.17;
}

.x_f8f8bgl {
  d: path("M21.6 20.8a9.47 9.47 0 1 1-9.47-9.46a9.47 9.47 0 0 1 9.47 9.46");
}

.y6f5i7mht {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.9 27.5a1.31 1.31 0 1 0 2.12-1.55a1.31 1.31 0 1 0-2.12 1.55");
}

.ysbj1jbfw {
  stop-color: var(--svg-color--4074ae, #4074ae);
}

.yt16mbc6i {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.49 16.3a1.01 1.01 0 0 0 1.63-1.2a1.01 1.01 0 0 0-1.63 1.2");
}

.z6a4c1b2v {
  fill: var(--svg-color--204a87, #204a87);
  fill-opacity: var(--svg-fill-opacity--0-71, 0.71);
  d: path("m21.32 19.34l-.26.3a6 6 0 0 0-.52-.51l-.4.06l-.37-.42v.5l.31.25l.21.24l.28-.32l.21.4v.4l-.31.35l-.58.4l-.43.44l-.28-.32l.14-.36l-.28-.32l-.47-1l-.4-.46l-.11.12l.16.57l.3.33a14 14 0 0 0 .55 1.43a8 8 0 0 0 1.01-.08v.27l-.41 1.03l-.39.43l-.31.68v1.1l.1.43l-.17.2l-.38.24l-.4.34l.33.37l-.46.4l.09.26l-.68.77h-.46l-.38.24h-.24v-.32l-.1-.63l-.42-1.18q0-.44.03-.87l.18-.4l-.25-.48l.02-.65l-.33-.37l.16-.54l-.26-.31h-.48l-.16-.18l-.47.3l-.2-.22l-.43.38l-.88-1.01l-.35-.83l.31-.47l-.17-.2l.38-.91q.48-.59.98-1.15l.6-.16l.65-.08l.46.12l.64.65l.23-.25l.31-.04l.6.2h.45l.31-.28l.14-.2l-.31-.2l-.52-.04a5 5 0 0 0-.46-.6l-.17.09l-.07.51l-.32-.35l-.07-.4l-.34-.28h-.14l.35.4l-.14.36l-.28.08l.17-.36l-.31-.16l-.28-.32l-.52.12l-.07.16l-.32.2l-.17.43l-.44.22l-.19-.22h-.21v-.7l.45-.24h.35l-.07-.28l-.27-.27l.47-.1l.26-.3l.2-.36h.39l-.1-.27l.24-.16v.32l.52.12l.52-.44l.04-.2l.45-.32l-.49.08v-.35l.18-.4h-.18l-.38.35l-.1.2l.1.28l-.17.47l-.28-.16l-.25-.27l-.38.27l-.14-.63l.66-.43v-.24l.42-.28l.66-.16l.46.16l.83.16l-.2.24h-.46l.45.47l.35-.4l.1-.17a12 12 0 0 1 2.1 2.5a9 9 0 0 1 1.13 3.2m-8.63-5.52l-.04.24l.25.16l.42-.27l-.21-.24l-.28.16zm.38-1.62l-.9-.36l-1.05.12l-1.3.35l-.24.24l.8.55v.32l-.31.32l.42.83l.28-.16l.35-.55a12 12 0 0 0 1.53-.6zm.94 3.31l-.14-.35l-.24.08l.07.43z");
}

.zhfakqbtq {
  stop-color: var(--svg-color--e7ebef, #e7ebef);
}

.zin1ubb9n {
  d: path("m29 24.1l-7.02 2.44l-.06.21l7.03-2.5z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

</style>
