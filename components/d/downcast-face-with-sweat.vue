<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGvvwSdekV" cx="64" cy="-1752.5" r="56.96" fx="64" fy="-1752.5" gradientTransform="matrix(1 0 0 -1 0 -1688)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient><radialGradient id="SVGcPC6pb1C" cx="26.76" cy="27.25" r="30.87" fx="26.76" fy="27.25" gradientTransform="matrix(1 0 0 1.39 0 -10.59)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="ruwj0vb6x"/><stop offset=".51" class="x3uwub1ak"/><stop offset=".87" class="jj-ds7b-i"/><stop offset="1" class="eljssxb3r"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGvvwSdekV)" class="r2y6kcc4l"/><path class="ad0a05yeh"/></g><path class="t2oc7xqiw"/><g class="wj4kgr0on"><path fill="url(#SVGcPC6pb1C)" class="s084_jbee"/><path class="oz85chbli"/></g><path class="kas--nbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:downcast-face-with-sweat" /></template>
<style>
.ad0a05yeh {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 31.27c5.33 8.6 8.11 18.84 8.11 30.23c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 112.12 44.81 120.4 64 120.4c15.4 0 29.8-5.2 40.4-14.5C115.9 95.7 122 81.4 122 64.5c0-12.74-3.47-24.06-10.11-33.23");
}

.eljssxb3r {
  stop-color: var(--svg-color--2489d6, #2489d6);
}

.jj-ds7b-i {
  stop-color: var(--svg-color--2b94db, #2b94db);
}

.kas--nbrt {
  fill: var(--svg-color--422b0d, #422b0d);
  stroke: var(--svg-color--422b0d, #422b0d);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m51.22 73.72l.18.05c2.62.94 4.87-2.55 2.1-4.31c-2.04-1.26-4.55-2.27-7.09-2.8c-7.1-1.75-14.31-.45-19.85 2.78c-2.68 1.64-.54 5.24 2.23 4.3c6.86-2.46 15-2.63 22.43-.02Zm47.9 0l.18.05c2.62.94 4.87-2.55 2.1-4.31c-2.04-1.26-4.55-2.27-7.09-2.8c-7.1-1.75-14.31-.45-19.85 2.78c-2.68 1.64-.54 5.24 2.23 4.3c6.86-2.46 15-2.63 22.43-.02Z");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.oz85chbli {
  fill: var(--svg-color--a1ebff, #a1ebff);
  d: path("M19.4 43.82c1.84 4.62 6.37 3.39 7.29-.93c.69-3.24-1-12.52-1.67-14.32s-2.47-1.39-3.35.93c-.74 1.94-4.09 9.74-2.26 14.32Z");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.r2y6kcc4l {
  d: path("M64 120.4c-27.9 0-58-17.5-58-55.9S36.1 8.6 64 8.6c15.5 0 29.8 5.1 40.4 14.4C115.9 33.2 122 47.6 122 64.5s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.ruwj0vb6x {
  stop-color: var(--svg-color--44b7eb, #44b7eb);
}

.s084_jbee {
  d: path("M29.66 58.12c-8.46 0-14.97-8.2-14.97-15.23c0-4.95 2.21-10.68 5.34-18.62c.39-1.17.91-2.34 1.43-3.65c1.49-3.72 2.81-7.75 4.81-11.24C27.63 7 31.1 7 32.41 9.41c1.86 3.43 3.14 7.14 5.07 11.47c5.47 12.24 7.03 17.18 7.03 22.13c.13 6.9-6.51 15.1-14.84 15.1Z");
}

.t2oc7xqiw {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64 90.49c9.58 0 15.8 7.01 17.48 10.29c.62 1.24.62 2.31.09 2.75q-.66.525-1.86 0c-.27-.09-.53-.27-.8-.44c-4.26-3.02-9.49-4.88-14.91-4.88s-10.65 1.86-14.91 4.79c-.27.18-.53.35-.8.44q-1.2.525-1.86 0c-.53-.53-.53-1.51.09-2.75c1.69-3.19 7.9-10.2 17.48-10.2");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.x3uwub1ak {
  stop-color: var(--svg-color--3dade6, #3dade6);
}

</style>
