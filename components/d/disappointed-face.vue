<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGhPFEudra" cx="64" cy="-1752" r="56.96" fx="64" fy="-1752" gradientTransform="matrix(1 0 0 -1 0 -1688)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><path fill="url(#SVGhPFEudra)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/><path class="ipb86_7zd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:disappointed-face" /></template>
<style>
.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.ipb86_7zd {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M64 88.3c10.8 0 17.8 7.9 19.7 11.6c.7 1.4.7 2.6.1 3.1q-.75.6-2.1 0c-.3-.1-.6-.3-.9-.5C76 99.1 70.1 97 64 97s-12 2.1-16.8 5.4c-.3.2-.6.4-.9.5q-1.35.6-2.1 0c-.6-.6-.6-1.7.1-3.1c1.9-3.6 8.9-11.5 19.7-11.5m10.37-19.5c-1.6 1.5-1.4 4 .5 5.3c2.4 1.7 5.8 3.8 9.7 4.8c3.9 1.1 7.9 1 10.8.8c2.3-.2 3.8-2.2 3.2-4.3c-.5-1.7-2.2-2.8-4.1-2.7c-2.2.2-5.2.2-8-.5c-2.8-.8-5.4-2.3-7.2-3.6c-1.5-1.1-3.6-1-4.9.2m-20.8 0c1.6 1.5 1.4 4-.5 5.3c-2.4 1.7-5.8 3.8-9.7 4.8c-3.9 1.1-7.9 1-10.8.8c-2.3-.2-3.8-2.2-3.1-4.3c.5-1.7 2.2-2.8 4.1-2.7c2.2.2 5.2.2 8-.5c2.8-.8 5.4-2.3 7.2-3.6c1.4-1.1 3.5-1 4.8.2");
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

</style>
