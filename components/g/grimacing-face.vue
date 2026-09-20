<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGLQb4bblj" cx="64" cy="-1160" r="56.96" fx="64" fy="-1160" gradientTransform="matrix(1 0 0 -1 0 -1096)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGLQb4bblj)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="mpzcubckm"/><path class="bycmrbc9p"/><path class="jf00rc3go"/><path class="bidon4b9e"/><g class="wj4kgr0on"><rect class="ci82u6f5j"/><path class="a982bccpm"/><path class="imrdl7bpe"/><path class="mujnknbcn"/><path class="ulpqcn9he"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:grimacing-face" /></template>
<style>
.a982bccpm {
  fill: var(--svg-color--937464, #937464);
  d: path("M62.5 72.2H65v23.95h-2.5z");
}

.bidon4b9e {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.79 45.97c-1.03-.72-2.58-.49-3.58.95c-1 1.45-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.bycmrbc9p {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.43 45.97c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.ci82u6f5j {
  width: 72.97px;
  height: 22.89px;
  x: 27.51px;
  y: 72.2px;
  fill: var(--svg-color--fff, #fff);
  rx: 11.44px;
  ry: 11.44px;
}

.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.imrdl7bpe {
  fill: var(--svg-color--937464, #937464);
  d: path("M27.51 82.52h72.97v2.5H27.51z");
}

.jf00rc3go {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.18 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mpzcubckm {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M44.82 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.42 8 9.42s8-3.54 8-9.42s-3.81-9.42-8-9.42");
}

.mujnknbcn {
  fill: var(--svg-color--937464, #937464);
  d: path("M75.67 72.2h2.5v23.95h-2.5zm-39.5 0h2.5v23.95h-2.5zm52.67 0h2.5v23.95h-2.5zm-39.51 0h2.5v23.95h-2.5z");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.ulpqcn9he {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M89.04 96.59H38.95c-7.14 0-12.94-5.81-12.94-12.94s5.81-12.94 12.94-12.94h50.09c7.14 0 12.94 5.81 12.94 12.94s-5.81 12.94-12.94 12.94M38.96 73.7c-5.48 0-9.94 4.46-9.94 9.94s4.46 9.94 9.94 9.94h50.09c5.48 0 9.94-4.46 9.94-9.94s-4.46-9.94-9.94-9.94z");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
