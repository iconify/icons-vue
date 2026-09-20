<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGzLaS2dSx" cx="64" cy="-2936" r="56.96" fx="64" fy="-2936" gradientTransform="matrix(1 0 0 -1 0 -2872)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGk6CiEzfR" cx="63.97" cy="89.51" r="33.82" fx="63.97" fy="89.51" gradientTransform="matrix(1 0 0 .46 0 48.18)" gradientUnits="userSpaceOnUse"><stop offset=".03"/><stop offset="1" class="a72as_i6q"/></radialGradient><radialGradient id="SVGK51pMcxL" cx="-49.67" cy="11.59" r="22.07" fx="-49.67" fy="11.59" gradientTransform="rotate(.36 -4250.321 13912.445)scale(1 .68)" gradientUnits="userSpaceOnUse"><stop offset=".03"/><stop offset=".97" class="a72as_i6q"/></radialGradient><radialGradient id="SVGMAOyYc1a" cx="104.21" cy="43.43" r="20.45" fx="104.21" fy="43.43" gradientTransform="rotate(179.64 97.563 5.742)scale(1 -.52)" href="#SVGk6CiEzfR"/><radialGradient id="SVG0xtzlcXp" cx="58.34" cy="83.95" r="11.51" fx="58.34" fy="83.95" gradientTransform="rotate(15.79 115.611 91.938)scale(1 1.19)" gradientUnits="userSpaceOnUse"><stop offset="0" class="ndyyyv-ps"/><stop offset=".15" class="x7xp6jbcy"/><stop offset=".46" class="t6ckkebhn"/><stop offset=".9" class="wdvt3zbjl"/><stop offset="1" class="wu5eqebdm"/></radialGradient><radialGradient id="SVGpjoruwGP" cx="203.84" cy="83.95" r="11.51" fx="203.84" fy="83.95" gradientTransform="rotate(164.21 124.011 -17.248)scale(1 -1.19)" href="#SVG0xtzlcXp"/><linearGradient id="SVGw6UGTghC" x1="113.66" x2="123.83" y1="53.29" y2="53.29" gradientUnits="userSpaceOnUse"><stop offset=".45" class="wk_lp_wlk"/><stop offset=".75" class="car3btb1d"/><stop offset=".97" class="a72as_i6q"/></linearGradient><linearGradient id="SVGLTJp0H2y" x1="116.87" x2="127.04" y1="53.29" y2="53.29" gradientTransform="matrix(-1 0 0 1 131.21 0)" href="#SVGw6UGTghC"/><linearGradient id="SVGqn6X3Rjl" x1="64" x2="64" y1="21.93" y2="57.99" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset="1" class="pilgl2bji"/></linearGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGzLaS2dSx)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><g class="wj4kgr0on"><circle class="up2da9nrg"/><circle class="aj77ifbjw"/><path class="ji8tw2bcy"/><path fill="url(#SVGk6CiEzfR)" class="x7c8wrf6z"/><path fill="url(#SVGK51pMcxL)" class="tb471qb3k"/><path fill="url(#SVGMAOyYc1a)" class="ynlzbzjdy"/><path class="go6oukmyw"/><path fill="url(#SVGw6UGTghC)" class="po5mtvbym"/><path class="m7l4o-bip"/><path fill="url(#SVGLTJp0H2y)" class="k4uh8jbtb"/><path fill="url(#SVGqn6X3Rjl)" class="wgh_1v-fy"/><path fill="url(#SVG0xtzlcXp)" class="g94r_lwvq"/><path fill="url(#SVGpjoruwGP)" class="g_vlneg2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:disguised-face" /></template>
<style>
.a72as_i6q {
  stop-color: var(--svg-color--424242, #424242);
}

.aj77ifbjw {
  cx: 93.39px;
  cy: 53.09px;
  r: 22.96px;
  fill: var(--svg-color--4fc3f7, #4fc3f7);
}

.car3btb1d {
  stop-color: var(--svg-color--323232, #323232);
}

.g_vlneg2z {
  d: path("M70.78 69.6c-1.75-3.71-2.21-10.29-2.21-10.29s1.63 1.81 4.95 6.62c.67.98 1.98 3.08 2.75 4.37c3.06 5.17 7.09 10.27 3.81 14.69c-1.68 2.26-4.01 2.22-5.43 2.58c-.43.11-.99.79-1.73 1.68s2.19-3.91 1.73-7.91s-2.12-8.04-3.87-11.75Z");
}

.g94r_lwvq {
  d: path("M57.25 69.6c1.75-3.71 2.21-10.29 2.21-10.29s-1.63 1.81-4.95 6.62c-.67.98-1.98 3.08-2.75 4.37c-3.06 5.17-7.09 10.27-3.81 14.69c1.68 2.26 4.01 2.22 5.43 2.58c.43.11.99.79 1.73 1.68s-2.19-3.91-1.73-7.91s2.12-8.04 3.88-11.75Z");
}

.go6oukmyw {
  fill: var(--svg-color--212121, #212121);
  d: path("M34.56 35.47c9.71 0 17.62 7.9 17.62 17.62s-7.9 17.62-17.62 17.62s-17.62-7.9-17.62-17.62s7.9-17.62 17.62-17.62m0-5.34c-12.68 0-22.96 10.28-22.96 22.96s10.28 22.96 22.96 22.96s22.96-10.28 22.96-22.96s-10.28-22.96-22.96-22.96m58.83 5.34c9.71 0 17.62 7.9 17.62 17.62s-7.9 17.62-17.62 17.62s-17.62-7.9-17.62-17.62s7.9-17.62 17.62-17.62m0-5.34c-12.68 0-22.96 10.28-22.96 22.96s10.28 22.96 22.96 22.96s22.96-10.28 22.96-22.96s-10.28-22.96-22.96-22.96");
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.ji8tw2bcy {
  fill: var(--svg-color--e1f5fe, #e1f5fe);
  d: path("m23.905 35.746l2.693-2.374L52.02 62.206l-2.693 2.375zM21.66 37.73l-6.24 5.82l25.42 28.84l6.24-5.83zm62.803-1.983l2.693-2.374l25.42 28.834l-2.693 2.375zM82.21 37.73l-6.24 5.82l25.42 28.84l6.25-5.83z");
}

.k4uh8jbtb {
  d: path("M12.83 60.54c-1.02-2.91-5.68-4.38-7.92-4.93c-.71-.17-1.22-.81-1.22-1.54v-3.15c0-.85.66-1.54 1.51-1.58c2.26-.11 6.39-.68 7.5-3.32c1.56-3.69 1.48 18.4.12 14.52Z");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.m7l4o-bip {
  fill: var(--svg-color--212121, #212121);
  d: path("M72.39 43.9s-.34 1.31-2.17 1.31s-2.63-1.48-6.22-1.48s-4.43 1.48-6.22 1.48s-2.17-1.3-2.17-1.31c-.56-.34-.25 6.07-.25 6.07c.19.63 1.26 6.87 1.85 6.95c0 0 2.45-4.31 6.79-4.36c4.33.05 6.79 4.36 6.79 4.36c.59-.08 1.66-6.32 1.85-6.95c0 0 .3-6.41-.25-6.07");
}

.ndyyyv-ps {
  stop-color: var(--svg-color--b36e00, #b36e00);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.po5mtvbym {
  d: path("M115.17 60.54c1.02-2.91 5.68-4.38 7.92-4.93c.71-.17 1.22-.81 1.22-1.54v-3.15c0-.85-.66-1.54-1.51-1.58c-2.26-.11-6.39-.68-7.5-3.32c-1.56-3.69-1.48 18.4-.12 14.52Z");
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.t6ckkebhn {
  stop-color: var(--svg-color--rgba-191-117-0-59, rgba(191, 117, 0, .59));
  stop-opacity: 0.59;
}

.tb471qb3k {
  d: path("M27.46 21.07c2.16 1.26 3.25 3.82 3.25 3.82s-3.09-2.29-8.14 1.07c-2.7 1.79-2.8 3.18-6.01 4.34c-.36.13-.47.61-.18.87c1.76 1.56 3.74 2.87 5.95 3.68c3.7 1.36 7.47-.63 11.29-.75c5.12-.17 11.75 1.28 16.3 3.86a16.8 16.8 0 0 0-.16-11.45c-1.26-3.29-3.59-6.15-6.54-8.07a.524.524 0 0 0-.81.51l.8 5.42c-2.3-3.49-5.91-5.59-10.12-5.45c-1.72.06-3.95.39-5.62 1.23c-.37.18-.37.7-.02.91Z");
}

.up2da9nrg {
  cx: 34.56px;
  cy: 53.09px;
  r: 22.96px;
  fill: var(--svg-color--4fc3f7, #4fc3f7);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wdvt3zbjl {
  stop-color: var(--svg-color--rgba-205-126-0-12, rgba(205, 126, 0, .12));
  stop-opacity: 0.12;
}

.wgh_1v-fy {
  d: path("M72.57 62.68c-2.32-7.75-3.55-12.34-8.55-12.36h-.06c-4.99.01-6.22 4.61-8.55 12.36C52.61 72 43.26 78.69 47.93 85c1.68 2.26 4.01 2.22 5.43 2.58c1.4.36 4.18 6.84 10.6 6.84h.06c6.42 0 9.2-6.47 10.6-6.84c1.42-.37 3.75-.32 5.43-2.58c4.67-6.31-4.68-13-7.48-22.32");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.wk_lp_wlk {
  stop-color: var(--svg-color--212121, #212121);
}

.wu5eqebdm {
  stop-color: var(--svg-color--d18100, #d18100);
  stop-opacity: 0;
}

.x7c8wrf6z {
  d: path("M96.68 87.93c.33-2.58-.58-5.39-2.1-7.43c-.2-.27-.63-.14-.64.19c-.07 1.71-.68 5.16-4.37 6.44c-6.97 2.42-10.42-9.38-20.51-8.43c-2.19.21-3.86 1.18-5.07 2.62l-.02-.02l-.02.02c-1.21-1.44-2.88-2.42-5.07-2.62c-10.1-.95-13.55 10.85-20.51 8.43c-3.69-1.28-4.3-4.73-4.37-6.44c-.01-.33-.44-.46-.64-.19c-1.52 2.04-2.44 4.85-2.1 7.43c.65 5 5.47 6.48 5.47 6.48c-1.34 1.26-2.63 1.59-4.18 1.47c-.5-.04-.82.56-.51.95c3.63 4.68 10.3 6.15 15.17 3.1c-.29.94-.75 1.82-1.34 2.56c-.24.31-.13.77.24.92c6.22 2.51 12.68 1.36 17.87-3.68c5.18 5.04 11.65 6.19 17.87 3.68c.36-.15.48-.61.24-.92a7.8 7.8 0 0 1-1.34-2.56c4.86 3.05 11.54 1.58 15.17-3.1c.31-.4 0-.99-.51-.95c-1.56.12-2.84-.21-4.18-1.47c0 0 4.82-1.48 5.47-6.48Z");
}

.x7xp6jbcy {
  stop-color: var(--svg-color--rgba-182-112-0-89, rgba(182, 112, 0, .89));
  stop-opacity: 0.89;
}

.ynlzbzjdy {
  d: path("M100.54 21.07c-2.16 1.26-3.25 3.82-3.25 3.82s3.09-2.29 8.14 1.07c2.7 1.79 2.8 3.18 6.01 4.34c.36.13.47.61.18.87c-1.76 1.56-3.74 2.87-5.95 3.68c-3.7 1.36-7.47-.63-11.29-.75c-5.12-.17-11.75 1.28-16.3 3.86a16.8 16.8 0 0 1 .16-11.45c1.26-3.29 3.59-6.15 6.54-8.07c.38-.25.87.06.81.51l-.8 5.42c2.3-3.49 5.91-5.59 10.12-5.45c1.72.06 3.95.39 5.62 1.23c.37.18.37.7.02.91Z");
}

</style>
