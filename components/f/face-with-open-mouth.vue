<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGzN46zeZf" cx="64" cy="-934" r="56.96" fx="64" fy="-934" gradientTransform="matrix(1 0 0 -1 0 -870)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGzN46zeZf)" class="uuo0vn6ns"/><path class="ba4-6rbxq"/></g><path class="g49jut8ag"/><path class="w3czb7b2p"/><path class="vwqvclubi"/><path class="jsu4cs3bf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-with-open-mouth" /></template>
<style>
.ba4-6rbxq {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37-7.35-48.18-22.94c10.76 17.66 31 25.94 50.18 25.94c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.g49jut8ag {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M84.8 89.02c0 8.16-9 13-20 13s-20-4.8-20-13s9-17 20-17s20 8.83 20 17m-40-46.98c-4.19 0-8 3.54-8 9.42s3.81 9.41 8 9.41c4.2 0 8-3.54 8-9.41s-3.76-9.42-8-9.42");
}

.jsu4cs3bf {
  fill: var(--svg-color--896024, #896024);
  d: path("M82.8 45.97a2.874 2.874 0 0 0-3.82 1.34c-.53 1.11-.29 2.44.6 3.3c1.42.68 3.13.08 3.82-1.34c.53-1.11.29-2.44-.6-3.3");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.vwqvclubi {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M83.2 42.04c-4.19 0-8 3.54-8 9.42s3.81 9.41 8 9.41s8-3.54 8-9.41s-3.81-9.42-8-9.42");
}

.w3czb7b2p {
  fill: var(--svg-color--896024, #896024);
  d: path("M44.45 45.97a2.874 2.874 0 0 0-3.82 1.34c-.53 1.11-.29 2.44.6 3.3c1.42.68 3.13.08 3.82-1.34c.53-1.11.29-2.44-.6-3.3");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
