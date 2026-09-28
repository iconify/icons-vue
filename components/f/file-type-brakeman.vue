<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><clipPath id="SVG9lTGpbFQ"><path class="fy5p3-b7n"/></clipPath><clipPath id="SVGPTYqXdBW"><path class="ox51brbqh"/></clipPath><clipPath id="SVGq1SWWbqG"><path class="xe82b8_nz"/></clipPath><clipPath id="SVGVZRXFbLF"><path class="j7ky1mqzm"/></clipPath><clipPath id="SVGXjpI7dzt"><path class="pqw6vhbpa"/></clipPath><clipPath id="SVGcb7qkcGa"><path class="yi5tafoua"/></clipPath><clipPath id="SVGW3YAedWh"><path class="ys-pi31wo"/></clipPath><clipPath id="SVG39c6icZe"><path class="nftvrpbvq"/></clipPath><radialGradient id="SVGo5rUuc2l" cx="0" cy="0" r="1" gradientTransform="matrix(53.72 0 0 -53.72 422.6 620)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ma40zdb6n"/><stop offset=".4" class="ma40zdb6n"/><stop offset=".9" class="a5rbasbst"/><stop offset="1" class="a5rbasbst"/></radialGradient><radialGradient id="SVGvSScDSzG" gradientTransform="matrix(33.643 0 0 -33.643 422.6 625)" href="#SVGo5rUuc2l"><stop offset="0" class="u8w0nvb1g"/><stop offset="1" class="lvr34s5qr"/></radialGradient><radialGradient id="SVGGFIf9uvq" gradientTransform="matrix(89.757 0 0 -89.757 420.1 614)" href="#SVGo5rUuc2l"><stop offset="0" class="as7t35i_d"/><stop offset=".4" class="as7t35i_d"/><stop offset=".9" class="u98ajzbtx"/><stop offset="1" class="u98ajzbtx"/></radialGradient><radialGradient id="SVGw4Rw7vXY" gradientTransform="matrix(52.641 0 0 -52.641 422.6 618)" href="#SVGo5rUuc2l"/><radialGradient id="SVGYGt0GcZF" gradientTransform="matrix(32.97 0 0 -32.97 422.6 623)" href="#SVGvSScDSzG"/></defs><g clip-path="url(#SVG9lTGpbFQ)" transform="matrix(.03661 0 0 -.03661 .6 42.2)" class="mc2zb0bvp"><path class="e_wjkwbtp"/><path fill="url(#SVGo5rUuc2l)" class="c1p_sdp9t"/><g clip-path="url(#SVGPTYqXdBW)" class="z4n2hhy8u"><g clip-path="url(#SVGq1SWWbqG)"><path fill="url(#SVGvSScDSzG)" class="xe82b8_nz"/></g></g><path class="wq4-t9jqs"/></g><path class="wxevgpuhu"/><path class="ew4166bgt"/><g clip-path="url(#SVGVZRXFbLF)" transform="matrix(.03661 0 0 -.03661 .6 42.2)"><path fill="url(#SVGGFIf9uvq)" class="j7ky1mqzm"/></g><path class="o2r8lrs1h"/><g clip-path="url(#SVGXjpI7dzt)" transform="matrix(.03661 0 0 -.03661 .6 42.2)"><path fill="url(#SVGw4Rw7vXY)" class="pqw6vhbpa"/></g><g clip-path="url(#SVGcb7qkcGa)" transform="matrix(.03661 0 0 -.03661 .6 42.2)" class="z4n2hhy8u"><g clip-path="url(#SVGW3YAedWh)"><path fill="url(#SVGYGt0GcZF)" class="ys-pi31wo"/></g></g><g class="g2csbibpu"><path class="giyu5obzl"/><path class="solwypbln"/><path class="jy0ah1r2l"/></g><g clip-path="url(#SVG39c6icZe)" transform="matrix(.03661 0 0 -.03661 .6 42.2)" class="n52mgrb1s"><path class="shlnebkox"/></g><path class="lmnsdih3e"/><path class="ug0lpe_wd"/><path class="ahfck-bxn"/><path class="i8g0pw1og"/><path class="k05fwebns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-brakeman" /></template>
<style>
.a5rbasbst {
  stop-color: var(--svg-color--9d1c29, #9d1c29);
}

.ahfck-bxn {
  d: path("M10.2 15a7 7 0 0 1-1.5-4.4a7.4 7.4 0 0 1 7.4-7.4a7.4 7.4 0 0 1 7.4 7.4q0 2.4-1.4 4.4h1.4a8.6 8.6 0 0 0-7.4-13a8.6 8.6 0 0 0-7.3 13zm13.2 7.2H8.7V21h14.7z");
}

.as7t35i_d {
  stop-color: var(--svg-color--f5865c, #f5865c);
}

.c1p_sdp9t {
  d: path("m371 632l26 44h52l26-44l-52-67z");
}

.e_wjkwbtp {
  fill: var(--svg-color--231f20, #231f20);
  d: path("m367 631l55-72l55 72l-28 48h-56zm55-91l-69 90l34 60h68l34-60z");
}

.ew4166bgt {
  fill: var(--svg-color--c51f36, #c51f36);
  d: path("M12.8 16.6q-.3.8-.3 1.8c0 2.4 1.6 4.4 3.5 4.4s3.4-2 3.4-4.4q0-.9-.3-1.8z");
}

.fy5p3-b7n {
  d: path("M354 690h137V541H354z");
}

.g2csbibpu {
  fill: var(--svg-color--231f20, #231f20);
}

.giyu5obzl {
  d: path("m16.8 18.2l-.3-.1l.5-.7l.2.1zm-1.5 0l-.3-.7l.2-.1l.4.7z");
}

.i8g0pw1og {
  d: path("M8.7 16.6a1.2 1.2 0 0 1 0-2v-1.3a2.4 2.4 0 0 0 0 4.6zm14.7-2a1.2 1.2 0 0 1 0 2V18a2.4 2.4 0 0 0 0-4.6zm-13 .9h11.4v-.3H10.3zm11.3 1.2H10.4q-1.2-.1-1.3-1.1V15q.1-1 1.3-1h11.3q1.2 0 1.3 1v.5q-.1 1-1.3 1");
}

.j7ky1mqzm {
  d: path("M334 699q-8-23-8-49c0-67 42-121 94-121s94 54 94 121c0 18-3 34-8 49z");
}

.jy0ah1r2l {
  d: path("M18 19.3h-.8V19h.9zm-4 0V19h.9v.3zm2.2 2.7H16v-1.4h.3z");
}

.k05fwebns {
  d: path("M18.5 16.5a4 4 0 0 1 .6 2.2c0 2-1.4 3.7-3 3.7s-3.2-1.6-3.2-3.7q0-1.3.7-2.2h-1a5 5 0 0 0-.5 2.2c0 2.5 1.7 4.6 4 4.6s3.9-2 3.9-4.6a5 5 0 0 0-.5-2.2z");
}

.lmnsdih3e {
  d: path("M10.4 14.2a1 1 0 0 0-.9.8v.4a1 1 0 0 0 .9.9h.9l-.2.6a8 8 0 0 0-.5 2.6q0 2.3 1.2 4.2v.7l-.3.1q-.6.3-.6.8v3q0 .7 1 .8h8.3q1 0 1-.9v-2.9q0-.6-.7-.8l-.6-.2l.4-.5a8 8 0 0 0 1.2-4.3q0-1.4-.4-2.6l-.2-.6h.8a1 1 0 0 0 .9-.9V15a1 1 0 0 0-.9-.8h-1.3v-1a1 1 0 0 0-.9-1h-1v-1.6h-5v1.7h-.9a1 1 0 0 0-.8.8v1zM20.2 30h-8.3c-1 0-2-.8-2-1.8v-2.9q0-.9 1-1.5a9 9 0 0 1-.9-6.6a2 2 0 0 1-1.4-1.8V15a2 2 0 0 1 1.8-1.7h.4V13a2 2 0 0 1 1.8-1.8V9.7h6.9v1.6a2 2 0 0 1 1.8 1.8v.2h.4a2 2 0 0 1 1.8 1.7v.4a2 2 0 0 1-1.4 1.8q.3 1 .3 2.3q0 2.4-1.1 4.3a2 2 0 0 1 .9 1.5v3c0 .9-1 1.7-2 1.7");
}

.lvr34s5qr {
  stop-color: var(--svg-color--f18051, #f18051);
}

.ma40zdb6n {
  stop-color: var(--svg-color--ec1e4b, #ec1e4b);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n52mgrb1s {
  opacity: var(--svg-opacity--0-4, 0.4);
}

.nftvrpbvq {
  d: path("M339 705h167v-96H339z");
}

.o2r8lrs1h {
  fill: var(--svg-color--231f20, #231f20);
  d: path("m12.9 28l-.2.2l-.2-.1v-2.6h.4zm1.3 0l-.1.2l-.2-.1v-2.6h.3zm1.4 0l-.1.2l-.2-.1v-2.6h.3zm1.4 0q0 .2-.2.2t-.1-.1v-2.6h.3zm1.4 0l-.2.2l-.1-.1v-2.6h.3zm1.3 0l-.1.2l-.2-.1v-2.6h.3zm-5.6-8.8l2 2.6l2-2.6l-1-1.7h-2zm2 3.2l-2.5-3.2l1.2-2.1h2.5l1.2 2.1z");
}

.ox51brbqh {
  d: path("M390 660h65v-70h-65z");
}

.pqw6vhbpa {
  d: path("m397 673l-25-43l50-66l50 66l-25 43z");
}

.shlnebkox {
  fill: var(--svg-color--f47d55, #f47d55);
  d: path("M423 679a84 84 0 0 0 83-71q1 6 1 13a84 84 0 1 1-167-13a84 84 0 0 0 83 71");
}

.solwypbln {
  d: path("m15 19.1l1 1.3l1-1.3l-.4-.8h-1zm1 1.8L14.8 19l.7-1.1h1.4l.6 1.1z");
}

.u8w0nvb1g {
  stop-color: var(--svg-color--771117, #771117);
}

.u98ajzbtx {
  stop-color: var(--svg-color--c51f36, #c51f36);
}

.ug0lpe_wd {
  d: path("M15.2 12.2a.4.4 0 1 1-.7 0a.4.4 0 0 1 .7 0m1.2 0a.4.4 0 1 1-.7 0a.4.4 0 0 1 .7 0m1.3 0a.4.4 0 1 1-.8 0a.4.4 0 0 1 .8 0M21 24.6H11v-1.1h10zm1 .3l-.8-1a5 5 0 0 0 .8-7.2l1-.7a6.4 6.4 0 0 1-1 8.9m-12 0a6.4 6.4 0 0 1-1-9l.9.8a5 5 0 0 0 .8 7.3z");
}

.wq4-t9jqs {
  fill: var(--svg-color--231f20, #231f20);
  d: path("m442 658l-7 4l12 19l7-4zm-39 0l-11 19l7 4l11-19zm395 633l28-36l28 36l-13 23h-29zm28-49l-37 49l18 31h38l18-31zm478 627l-23 2v8l23-2zm-110 0v8l23 2v-8zm59-74h-8v37h8z");
}

.wxevgpuhu {
  fill: var(--svg-color--6c6c71, #6c6c71);
  d: path("M21.7 14.4h-1.5V13q0-.5-.7-.6h-1.1v-1.7h-4.7v1.7h-1q-.7 0-.7.6v1.3h-1.6q-.6 0-.7.6v.4q0 .7.7.7h1.2a8 8 0 0 0-.8 3.4q0 2.4 1.2 4.2v1q-.9 0-1 .6v3q.1.5 1 .6h8.2q.8 0 .8-.7v-2.9q0-.6-.8-.7h-.5v-.4q1.6-1.9 1.6-4.7a8 8 0 0 0-.8-3.4h1.2q.6 0 .7-.7V15q0-.5-.7-.6");
  opacity: var(--svg-opacity--0-8, 0.8);
}

.xe82b8_nz {
  d: path("m390 633l16 27h34l16-27l-32-42z");
}

.yi5tafoua {
  d: path("M391 657h64v-68h-64z");
}

.ys-pi31wo {
  d: path("m391 630l15 27h33l15-27l-32-42z");
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

</style>
