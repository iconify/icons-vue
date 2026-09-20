<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGhPFEudra" cx="64" cy="-1752" r="56.96" fx="64" fy="-1752" gradientTransform="matrix(1 0 0 -1 0 -1688)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGhPFEudra)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="socs_ccav"/><path class="u6x_yydcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:confounded-face" /></template>
<style>
.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
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

.socs_ccav {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M58.25 64.11C56.84 63.25 36.29 51 35.36 50.44c-2.31-1.4-3.7-.63-4.46.26c-1.03 1.21-.75 3.01.65 4.28c.55.5 11.57 9.66 13.57 11.33c-2.07 1.24-12.77 7.66-14.34 8.75c-1.79 1.23-2.03 3.21-1.53 4.16c.35.66 1.18 1.17 2.36 1.15c.6 0 1.29-.15 2.05-.47l24.27-9.43c1.13-.42 1.91-1.5 2.04-2.84c.14-1.44-.53-2.79-1.73-3.52Zm10.32 0c1.41-.86 21.96-13.11 22.89-13.67c2.31-1.4 3.7-.63 4.46.26c1.03 1.21.75 3.01-.65 4.28c-.55.5-11.57 9.66-13.57 11.33c2.07 1.24 12.77 7.66 14.34 8.75c1.79 1.23 2.03 3.21 1.53 4.16c-.35.66-1.18 1.17-2.36 1.15c-.6 0-1.29-.15-2.05-.47l-24.27-9.43c-1.13-.42-1.91-1.5-2.04-2.84c-.14-1.44.53-2.79 1.73-3.52Z");
}

.u6x_yydcd {
  fill: var(--svg-color--35220b, #35220b);
  d: path("M95.98 88.24c-1.17-1.03-3.3-1.16-4.53-.01l-5.02 4.2l-8.18-7.93c-1.79-2.03-4.98-1.91-6.53-.01l-7.54 8.19l-7.54-8.19c-1.55-1.89-4.74-2.01-6.53.01l-8.18 7.93l-5.02-4.2c-1.23-1.15-3.36-1.02-4.53.01s-.74 2.55.58 4.22l6.12 7.32c1.83 1.46 4.69 1.43 6.49-.05l7.79-7.09l7.53 8.13c.8.95 2.13 1.36 3.3 1.36s2.47-.47 3.3-1.36l7.53-8.13l7.79 7.09c1.8 1.48 4.65 1.5 6.49.05l6.12-7.32c1.32-1.67 1.74-3.18.58-4.22Z");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
