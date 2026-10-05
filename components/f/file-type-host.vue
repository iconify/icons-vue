<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG73m99b7z" x1="102" x2="105" y1="156" y2="156" gradientTransform="matrix(-.864 0 0 .864 115 -122)" gradientUnits="userSpaceOnUse"><stop offset="0" class="zhfakqbtq"/><stop offset="1" class="kdm06vb1s"/></linearGradient><linearGradient id="SVGgQ2q5bcA" x1="97.2" x2="94.9" y1="146" y2="150" gradientTransform="matrix(.827 .25 -.25 .827 -16.3 -121)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="vc--wpv5i"/></linearGradient><linearGradient id="SVGuktrkdnU" x1="97.2" x2="94.9" y1="146" y2="150" gradientTransform="matrix(.827 .25 -.25 .827 -16.3 -121)" gradientUnits="userSpaceOnUse"><stop offset="0"/><stop offset="1" class="co03y-bdw"/></linearGradient><linearGradient id="SVG5Aa1pJyG" x1="96.9" x2="94.6" y1="147" y2="151" gradientTransform="matrix(.827 .25 -.25 .827 -15.9 -122)" href="#SVGgQ2q5bcA"/><linearGradient id="SVGLSFQAccQ" x1="96.9" x2="94.6" y1="147" y2="151" gradientTransform="matrix(.827 .25 -.25 .827 -15.9 -122)" href="#SVGuktrkdnU"/><linearGradient id="SVGrMHBOdTV" x1="96.6" x2="94.3" y1="148" y2="152" gradientTransform="matrix(.827 .25 -.25 .827 -15.4 -124)" href="#SVGgQ2q5bcA"/><linearGradient id="SVGU1pNwc6h" x1="96.6" x2="94.3" y1="147" y2="152" gradientTransform="matrix(.827 .25 -.25 .827 -15.4 -124)" href="#SVGuktrkdnU"/><linearGradient id="SVGiSaOkdSu" x1="96.3" x2="94" y1="148" y2="153" gradientTransform="matrix(.827 .25 -.25 .827 -15 -125)" href="#SVGgQ2q5bcA"/><linearGradient id="SVG5ItmAgFY" x1="96.3" x2="94" y1="148" y2="152" gradientTransform="matrix(.827 .25 -.25 .827 -15 -125)" href="#SVGuktrkdnU"/><linearGradient id="SVGamZK0b0w" x1="96" x2="93.7" y1="149" y2="153" gradientTransform="matrix(.827 .25 -.25 .827 -14.6 -127)" href="#SVGgQ2q5bcA"/><linearGradient id="SVGM4qFHCpZ" x1="96" x2="93.7" y1="149" y2="153" gradientTransform="matrix(.827 .25 -.25 .827 -14.6 -127)" href="#SVGuktrkdnU"/><linearGradient id="SVGbirGWWtD" x1="-69.9" x2="-68.4" y1="5.01" y2="8.62" gradientTransform="matrix(.939 -.879 -.683 -.73 84.9 -29.9)" href="#SVGSsJfle9M"/><linearGradient id="SVGkF8GldVk" x1="-26.7" x2="-25.3" y1="33.6" y2="38" gradientTransform="matrix(1.13 .613 .477 -.879 21.4 69.8)" href="#SVGSsJfle9M"/><linearGradient id="SVGvutc8dib" x1="-67.4" x2="-67.5" y1="8.4" y2="5.62" gradientTransform="matrix(.918 -.859 -.668 -.713 78 -32.8)" href="#SVGSsJfle9M"/><linearGradient id="SVGPB2nfevh" x1="-93" x2="-92.6" y1="95.8" y2="98.6" gradientTransform="matrix(-1.28 -.126 -.098 .995 -97.1 -90.8)" href="#SVGSsJfle9M"/><radialGradient id="SVGKCCxCdXa" cx="7.98" cy="19" r="16.6" gradientTransform="matrix(.883 0 0 -.883 1.99 33.7)" gradientUnits="userSpaceOnUse"><stop offset="0" class="n45-qabho"/><stop offset=".155" class="n45-qabho"/><stop offset=".75" class="ysbj1jbfw"/><stop offset="1" class="kjsw3bzhe"/></radialGradient><radialGradient id="SVGzzb4be2c" cx="6.52" cy="21" r="24.1" gradientTransform="matrix(.883 0 0 -.883 1.99 33.7)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="opfzlzbej"/></radialGradient><radialGradient id="SVGSsJfle9M" cx="-34.8" cy="8.18" r="3.72" gradientTransform="rotate(143.75 -13.597 17.526)scale(.883)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="SVG2F99BbNo" cx="-32.9" cy="32.7" r="3.72" gradientTransform="rotate(143.74 -8.59 41.032)scale(1.145)" href="#SVGSsJfle9M"/><radialGradient id="SVGTubwGb6s" cx="-38.8" cy="12.7" r="3.72" gradientTransform="rotate(143.75 -16.044 23.312)scale(.883)" href="#SVGSsJfle9M"/><radialGradient id="SVG5OR3CbtV" cx="-30.8" cy="15.4" r="3.72" gradientTransform="matrix(-.768 .564 -.563 -.768 -2.96 44.7)" href="#SVGSsJfle9M"/></defs><path class="hbdbfw2ok"/><path class="hxgtu-v3n"/><path class="y_ukrmb-s"/><path class="zaz9x9zog"/><path class="sttdiu-js"/><path class="uxr9mhb9b"/><path fill="url(#SVG73m99b7z)" class="mm_me1xuu"/><path class="orcxgko1i"/><path class="b0_g9vbuz"/><path fill="url(#SVGgQ2q5bcA)" class="xiqtk3y2g"/><path fill="url(#SVGuktrkdnU)" class="ofihh_b4y"/><path fill="url(#SVG5Aa1pJyG)" class="qntcdlnko"/><path fill="url(#SVGLSFQAccQ)" class="vge3ypb6m"/><path fill="url(#SVGrMHBOdTV)" class="dr1iq9z8k"/><path fill="url(#SVGU1pNwc6h)" class="krvxzp45v"/><path fill="url(#SVGiSaOkdSu)" class="moniccber"/><path fill="url(#SVG5ItmAgFY)" class="jepp7cbqf"/><path fill="url(#SVGamZK0b0w)" class="tut0bpblu"/><path fill="url(#SVGM4qFHCpZ)" class="yg5epwbiw"/><path fill="url(#SVGKCCxCdXa)" class="x_f8f8bgl"/><path class="bfudfixhq"/><path class="r61q1obrt"/><path class="jfedbbyej"/><path class="zc17fqb0p"/><path fill="url(#SVGzzb4be2c)" class="achvonb4w"/><path fill="url(#SVGSsJfle9M)" class="keo5mub7t"/><path class="yt16mbc6i"/><path fill="url(#SVG2F99BbNo)" class="n8-pqacla"/><path class="y6f5i7mht"/><path fill="url(#SVGTubwGb6s)" class="u3hwwvwjx"/><path class="g26w4kc7z"/><path fill="url(#SVG5OR3CbtV)" class="nya3njelz"/><path class="kr0zh22lr"/><path fill="url(#SVGbirGWWtD)" class="jqcwfzbel"/><path fill="url(#SVGkF8GldVk)" class="ck2xklbhz"/><path fill="url(#SVGvutc8dib)" class="z4quetbeg"/><path fill="url(#SVGPB2nfevh)" class="tn9mmwb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-host" /></template>
<style>
.achvonb4w {
  d: path("M12.1 30a9.23 9.23 0 1 1 9.23-9.23A9.23 9.23 0 0 1 12.1 30m0-18a8.74 8.74 0 1 0 8.74 8.74A8.75 8.75 0 0 0 12.1 12");
  opacity: var(--svg-opacity--0-396, 0.396);
}

.b0_g9vbuz {
  fill: var(--svg-color--fff, #fff);
  d: path("m24.1 13.8l3-1.1l-.2-.1l-2.7 1v-.3l-.1-.2z");
  opacity: var(--svg-opacity--0-72, 0.72);
}

.bfudfixhq {
  fill: var(--svg-color--39396c, #39396c);
  d: path("M12.1 30.5a9.71 9.71 0 1 1 9.71-9.71a9.71 9.71 0 0 1-9.71 9.71m0-18.9a9.22 9.22 0 1 0 9.22 9.22a9.23 9.23 0 0 0-9.22-9.22");
}

.ck2xklbhz {
  d: path("M16.5 27a16.4 16.4 0 0 1-7.44-2.2c-4.98-2.7-7.87-6.68-6.57-9.06c.63-1.16 2.15-1.73 4.3-1.6a17.2 17.2 0 0 1 6.88 2.17a17.2 17.2 0 0 1 5.57 4.58c1.28 1.73 1.64 3.32 1 4.48c-.591 1.09-1.95 1.63-3.73 1.63zM6.2 14.6c-1.67 0-2.85.488-3.34 1.4c-1.16 2.13 1.71 5.94 6.4 8.48s9.44 2.87 10.6.736c.546-1.01.2-2.43-.972-4.02a16.7 16.7 0 0 0-5.43-4.46a16.7 16.7 0 0 0-6.7-2.11q-.289-.024-.56-.024z");
}

.co03y-bdw {
  stop-color: var(--svg-color--6a6a6a, #6a6a6a);
}

.dr1iq9z8k {
  d: path("m29 23.2l-7.02 2.44l-.066.218l7.03-2.52l.054-.138z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.g26w4kc7z {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.95 22.8a1.01 1.01 0 1 0 1.63-1.2a1.01 1.01 0 1 0-1.63 1.2");
}

.hbdbfw2ok {
  fill: var(--svg-color--00608b, #00608b);
  stroke: var(--svg-color--000, #000);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-28px, 1.28px);
  d: path("M11 4.113a.746.746 0 0 0-.611.665v.056c0 .214.26 17.006.26 17.172a.84.84 0 0 0 .222.44c.166.166 9.417 7.2 9.582 7.312l.056.056c.166.167.277.167.665.112h.112c.832-.222 8.041-3.106 8.041-3.106c.222-.112.277-.222.277-.5l.114-17.235a1.2 1.2 0 0 0-.387-.832c-.056-.056-.056-.112-.112-.112c-.333-.166-10.269-5.992-10.435-6.048a1.9 1.9 0 0 0-.942.056c-.333.11-6.562 1.9-6.839 1.953ZM20.8 29.7ZM11.168 4.935a3.5 3.5 0 0 1-.493-.333c.222.167 1.054.722 2 1.387c-.561-.443-1.054-.776-1.441-1.054c-.222-.166-.387-.277-.387-.277a3 3 0 0 0 .333.277Z");
}

.hxgtu-v3n {
  fill: var(--svg-color--00608b, #00608b);
  d: path("m17.864 2.088l.056-.056c-.332.112-6.7 2-6.963 2.087c-.233.078-.564.373-.4.539s9.565 6.59 9.731 6.7a1.2 1.2 0 0 0 1 .056c.273-.056 7.538-2.439 7.925-2.551c.387-.166.277-.5 0-.665c-.331-.217-10.243-6.107-10.413-6.163a1.9 1.9 0 0 0-.942.056Z");
}

.jepp7cbqf {
  d: path("m29.1 22.1l-7.06 2.45l-.064.212l7.05-2.54l.067-.124z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.jfedbbyej {
  fill: var(--svg-color--204a87, #204a87);
  fill-opacity: var(--svg-fill-opacity--0-713, 0.713);
  d: path("m14.153 15.454l-.07.474l.383-.08l.279-.276l-.245-.239a6 6 0 0 0-.279-.631h-.209v.239l.139.159v.355m-5.159 7.496l-.279-.551l-.523-.12l-.279-.749l-.7.08l-.592-.434l-.628.552v.087a2.4 2.4 0 0 1-.592-.167l-.139-.4v-.435l-.418.039q.053-.414.1-.828H4.7l-.244.319l-.244.118l-.345-.2l-.035-.434l.07-.473l.523-.4h.414l.069-.239l.523.118l.383.474l.07-.79l.667-.548l.244-.592l.488-.2l.279-.4l.627-.119l.311-.459h-.94l.593-.277h.418l.593-.2l.07-.239l-.21-.2l-.244-.084l.07-.239l-.175-.355l-.418.159l.07-.319l-.488-.277l-.385.677l.035.239l-.383.159l-.244.512l-.1-.473l-.662-.273l-.1-.356l.872-.513l.383-.355l.035-.434l-.209-.119l-.279-.04l-.175.434s-.292.057-.367.076a9.96 9.96 0 0 0-3.34 6.383a5 5 0 0 0 .326.567l.732.434l.732.2l.314.4l.488.355L5.79 22l.21.1v.064l-.279.749l-.21.319l.07.159l-.181.589l.627 1.145l.627.552l.279.4l-.033.813l.21.473l-.21.912s-.017-.006.01.085A4.2 4.2 0 0 0 8.1 29l.128-.1l-.069-.2l.279-.277l.1-.277l.454-.159l.348-.868l-.1-.239l.244-.355l.523-.119l.279-.631l-.07-.789l.418-.592l.07-.592c-.572-.284-1.14-.576-1.708-.868m-.771-8.941l.348.239h.279v-.278l-.352-.16l-.279.2");
}

.jqcwfzbel {
  d: path("M9.36 30.4a3.05 3.05 0 0 1-2.32-.866c-.9-.964-.956-2.59-.159-4.59a17.2 17.2 0 0 1 4.23-5.84c4.13-3.87 8.82-5.35 10.7-3.37c.9.965.956 2.59.159 4.59a17.2 17.2 0 0 1-4.23 5.84a17.2 17.2 0 0 1-6.11 3.83a7.4 7.4 0 0 1-2.24.403zm10.1-15.1c-2.15 0-5.26 1.52-8.05 4.13a16.7 16.7 0 0 0-4.12 5.69c-.734 1.83-.707 3.3.075 4.13s2.24.956 4.12.348a16.7 16.7 0 0 0 5.95-3.74a16.7 16.7 0 0 0 4.12-5.68c.734-1.83.708-3.3-.076-4.13a2.66 2.66 0 0 0-2.02-.744z");
}

.kdm06vb1s {
  stop-color: var(--svg-color--c4ce00, #c4ce00);
}

.keo5mub7t {
  d: path("M3.66 17.6a3.28 3.28 0 0 0 5.35-3.79q-.031-.044-.064-.087a3.28 3.28 0 0 0-5.29 3.88z");
}

.kjsw3bzhe {
  stop-color: var(--svg-color--36486c, #36486c);
}

.kr0zh22lr {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.1 16.2a1.09 1.09 0 0 0 1.77-1.28l-.007-.009a1.09 1.09 0 0 0-1.77 1.28z");
}

.krvxzp45v {
  d: path("m29.1 23l-7.06 2.45l-.064.212l7.05-2.54l.067-.124z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.mm_me1xuu {
  d: path("m26.9 12.3l-2.7 1v.3l2.7-1z");
}

.moniccber {
  d: path("m29 22.3l-7.02 2.44l-.064.212l7.04-2.52z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.n45-qabho {
  stop-color: var(--svg-color--d3e9ff, #d3e9ff);
}

.n8-pqacla {
  d: path("M13.6 29.2a4.25 4.25 0 0 0 6.91-4.96l-.053-.072a4.25 4.25 0 0 0-6.86 5.03z");
}

.nya3njelz {
  d: path("M9.14 17.6a3.54 3.54 0 0 0 5.73-4.16l-.019-.026a3.54 3.54 0 0 0-5.73 4.16z");
}

.ofihh_b4y {
  d: path("m29.1 24.8l-7.06 2.45l-.064.212l7.05-2.54l.067-.124z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.opfzlzbej {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0.165;
}

.orcxgko1i {
  d: path("m26.9 12.3l-2.7 1l-.1-.2l3-1v.6l-.2-.1z");
  opacity: var(--svg-opacity--0-22, 0.22);
}

.qntcdlnko {
  d: path("m29 24.1l-7.02 2.44l-.064.212l7.03-2.51l.053-.14z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.r61q1obrt {
  fill: var(--svg-color--204a87, #204a87);
  fill-opacity: var(--svg-fill-opacity--0-713, 0.713);
  d: path("m21.321 19.341l-.261.3a6 6 0 0 0-.523-.513l-.4.059l-.367-.414v.506l.314.239l.209.239l.279-.319l.21.4v.4l-.314.355l-.575.4l-.435.434l-.279-.319l.139-.355l-.279-.319l-.471-1.006l-.4-.454l-.112.113l.159.572l.3.336a14 14 0 0 0 .558 1.421a8 8 0 0 0 1.011-.08v.277l-.418 1.026l-.383.434l-.314.672v1.105l.105.434l-.175.2l-.384.239l-.4.336l.332.375l-.454.4l.087.256l-.68.77h-.457l-.383.239h-.245v-.319l-.1-.632c-.135-.4-.276-.79-.418-1.183c0-.29.018-.578.035-.868l.175-.4l-.245-.474l.018-.651l-.332-.375l.166-.542l-.269-.306h-.475l-.159-.178l-.471.3l-.191-.218l-.436.375l-.885-1.011l-.348-.829l.314-.473l-.175-.2l.383-.908c.315-.391.643-.768.976-1.145l.593-.159l.662-.08l.454.119l.645.65l.226-.256l.313-.039l.593.2h.455l.314-.277l.139-.2l-.314-.2l-.523-.039a5 5 0 0 0-.453-.592l-.175.08l-.07.513l-.314-.355l-.069-.4l-.348-.276h-.14l.349.4l-.139.355l-.279.08l.175-.355l-.314-.159l-.278-.319l-.524.118l-.069.159l-.314.2l-.175.434l-.435.217l-.192-.217h-.211v-.705l.454-.239h.348l-.07-.276l-.277-.274l.47-.1l.261-.3l.209-.355h.384l-.105-.276l.244-.155v.316l.523.118l.522-.437l.035-.2l.453-.319a3.5 3.5 0 0 0-.488.08v-.354l.175-.4h-.175l-.383.355l-.105.2l.105.277l-.175.473l-.279-.159l-.244-.276l-.384.276l-.139-.631l.662-.434v-.239l.418-.276l.662-.159l.454.159l.836.159l-.209.239h-.454l.454.473l.348-.4l.106-.174a12.4 12.4 0 0 1 2.1 2.508a9.1 9.1 0 0 1 1.125 3.182m-8.634-5.506l-.035.239l.245.159l.418-.276l-.209-.239l-.279.159l-.139-.04m.383-1.619l-.907-.355l-1.046.115l-1.29.355l-.244.239l.8.552v.319l-.314.319l.418.829l.278-.159l.349-.552a12 12 0 0 0 1.533-.592l.418-1.066m.946 3.311l-.139-.356l-.245.08l.07.434z");
}

.sttdiu-js {
  fill: var(--svg-color--00608b, #00608b);
  d: path("M29.328 8.645c-.056 0-8.143 2.772-8.614 2.772c-.611 0-5.063-3.477-6.188-4.076c1.183 1.057 5.375 4.02 5.54 4.131c.332.222.517.42.517.7l.1.674l.054-.662c0-.277.163-.377.44-.489s7.153-2.5 8.151-2.828a.346.346 0 0 1 .333.277a1.22 1.22 0 0 0-.5-.942c.166.163.222.44.166.44Z");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tn9mmwb1y {
  d: path("M13.2 24.9q-1.026.001-2.12-.106c-5.63-.555-9.84-3.1-9.58-5.8s4.89-4.38 10.5-3.82s9.84 3.1 9.57 5.8c-.23 2.35-3.77 3.92-8.4 3.92zM1.9 19.04c-.239 2.42 3.88 4.81 9.19 5.33s9.81-1.02 10.1-3.43s-3.88-4.8-9.19-5.33s-9.81 1.02-10 3.43z");
}

.tut0bpblu {
  d: path("m29 21.4l-7.02 2.44l-.064.212l7.03-2.52z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.u3hwwvwjx {
  d: path("M3.12 24.2a3.28 3.28 0 1 0 5.29-3.88a3.28 3.28 0 0 0-5.29 3.88");
}

.uxr9mhb9b {
  fill: var(--svg-color--00608b, #00608b);
  d: path("M14.7 7.48a3 3 0 0 1 .5.333zm5.657 22.3c.327.128.37-.173.37-.173a.41.41 0 0 0 .412.332a.675.675 0 0 1-.782-.16ZM10.7 4.741c-.3-.352.258-.628.258-.628c-.693.2-.7.635-.662.881c.009-.238.126-.382.4-.248Z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vge3ypb6m {
  d: path("m29.1 23.9l-7.05 2.44l-.064.212l7.05-2.54l.067-.124z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.x_f8f8bgl {
  d: path("M21.6 20.8a9.47 9.47 0 1 1-9.47-9.46a9.47 9.47 0 0 1 9.47 9.46");
}

.xiqtk3y2g {
  d: path("m29 24.9l-7.02 2.44l-.064.212l7.03-2.52l.055-.138z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.y_ukrmb-s {
  fill: var(--svg-color--00608b, #00608b);
  d: path("M29.5 26.316c0 .277-.056.387-.277.5c0 0-7.209 2.884-8.041 3.106a.345.345 0 0 1-.5-.333c0-.222-.112-17.291-.112-17.512s.163-.333.44-.5c.277-.222 8.1-2.772 8.263-2.828c.222-.053.387.11.387.387Z");
}

.y6f5i7mht {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.9 27.5a1.31 1.31 0 1 0 2.12-1.55a1.31 1.31 0 1 0-2.12 1.55");
}

.yg5epwbiw {
  d: path("m29.1 21.2l-7.06 2.45l-.064.212l7.05-2.54z");
  opacity: var(--svg-opacity--0-13, 0.13);
}

.ysbj1jbfw {
  stop-color: var(--svg-color--4074ae, #4074ae);
}

.yt16mbc6i {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.49 16.3a1.01 1.01 0 0 0 1.63-1.2a1.01 1.01 0 0 0-1.63 1.2");
}

.z4quetbeg {
  d: path("M7.22 28.6a3 3 0 0 1-2.27-.849c-.885-.946-.941-2.54-.159-4.49a16.8 16.8 0 0 1 4.14-5.71c4.04-3.78 8.63-5.23 10.4-3.29c1.81 1.94.066 6.42-3.98 10.2a16.8 16.8 0 0 1-5.97 3.75a7.2 7.2 0 0 1-2.2.397zm9.86-14.8c-2.1 0-5.13 1.49-7.86 4.04a16.3 16.3 0 0 0-4.02 5.55c-.717 1.78-.69 3.22.072 4.03s2.19.934 4.02.338a16.4 16.4 0 0 0 5.81-3.65c3.8-3.56 5.57-7.85 3.96-9.58a2.6 2.6 0 0 0-1.97-.721z");
}

.zaz9x9zog {
  fill: var(--svg-color--00608b, #00608b);
  d: path("m20.4 29.812l.056.056c-.112-.166-9.437-7.277-9.6-7.443a.42.42 0 0 1-.222-.387c0-.17-.314-16.883-.314-17.048c-.056-.167.056-.5.277-.333s9.64 6.7 9.805 6.813a.68.68 0 0 1 .277.555c0 .222.068 17.18.068 17.458c0 .313-.179.443-.345.332Z");
}

.zc17fqb0p {
  fill: var(--svg-color--204a87, #204a87);
  fill-opacity: var(--svg-fill-opacity--0-713, 0.713);
  d: path("m7.319 13.678l-.175.434h.349l.175-.4q.225-.16.453-.319l.349.119l.7.473l.349-.319l-.384-.159l-.175-.355l-.662-.08l-.035-.2l-.314.08l-.139.276l-.175-.355l-.069.159l.035.4l-.279.239m1.252-.981l.175-.159l.349-.08a5.5 5.5 0 0 1 .732-.277l-.139-.239l-.45.065l-.213.212l-.351.051l-.312.147l-.151.073l-.092.124l.453.08m.592 3.753l.21-.319l-.314-.239l.1.552");
}

.zhfakqbtq {
  stop-color: var(--svg-color--e7ebef, #e7ebef);
}

</style>
