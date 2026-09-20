<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><radialGradient id="SVGoKudkdAK" cx="64" cy="-864" r="56.96" fx="64" fy="-864" gradientTransform="matrix(1 0 0 -1 0 -800)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><g class="wj4kgr0on"><path fill="url(#SVGoKudkdAK)" class="uuo0vn6ns"/><path class="gwi4hgb1m"/></g><path class="t_5dqfb4j"/><path class="vajwg7yal"/><path class="ygudl7bvr"/><path class="mq758tb1q"/><path class="k_z80xmbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-with-raised-eyebrow" /></template>
<style>
.gwi4hgb1m {
  fill: var(--svg-color--eb8f00, #eb8f00);
  d: path("M111.89 30.77C117.22 39.37 120 49.61 120 61c0 16.9-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5c-18.06 0-37.04-7.35-48.18-22.94C24.58 111.62 44.81 119.9 64 119.9c15.4 0 29.8-5.2 40.4-14.5C115.9 95.2 122 80.9 122 64c0-12.74-3.47-24.06-10.11-33.23");
}

.k_z80xmbv {
  fill: var(--svg-color--3f2c13, #3f2c13);
  d: path("M27.8 46.7c2.5-6.34 10.2-9.81 16.4-6.6c2.93 1.49 6.11 3.01 9.5 2.8c.99-.15 1.9-.7 2.6-1.4c1-.71 2.38-.49 3.1.5c1.7 2.75-2.33 4.88-4.5 5.6c-3.02.94-6.26.43-9.2-.6c-2.96-1.01-5.86-3.12-9.1-1.9c-2.05.82-3.82 2.29-5.2 4c-1.57 1.78-4.56-.29-3.6-2.4");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.mq758tb1q {
  fill: var(--svg-color--896024, #896024);
  d: path("M81.3 49.54c-1.25-.15-2.51.78-2.71 2.53s.81 2.94 2.06 3.08c1.25.15 2.51-.78 2.71-2.53s-.81-2.94-2.06-3.08");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.t_5dqfb4j {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M86 88.72H42c-2.2 0-4-1.8-4-4s1.8-4 4-4h44c2.2 0 4 1.8 4 4s-1.8 4-4 4m9.56-51.92c-1.5-2.01-2.34-4.44-4.35-5.6c-2.94-.59-6.21 1.77-9.33 3.91c-1.81 1.24-3.95 2.99-5.38 2.99c-1.01 0-1.98-.12-2.38-1.83c-.52-2.15 4.07-5.24 6.23-6.48s7.77-4.61 11.14-4.19c3.58.45 6.45 3.3 8.02 9.2v.1c.88 2.47-2.45 4.07-3.95 1.9M45.53 51.71c-4.19 0-8 2.99-8 7.95s3.81 7.95 8 7.95s8-2.99 8-7.95s-3.81-7.95-8-7.95");
}

.uuo0vn6ns {
  d: path("M64 119.9c-27.9 0-58-17.5-58-55.9S36.1 8.1 64 8.1c15.5 0 29.8 5.1 40.4 14.4C115.9 32.7 122 47.1 122 64s-6.1 31.2-17.6 41.4c-10.6 9.3-25 14.5-40.4 14.5");
}

.vajwg7yal {
  fill: var(--svg-color--896024, #896024);
  d: path("M45.4 54.61c-1.03-.72-2.58-.49-3.58.95s-.67 2.97.36 3.69s2.58.49 3.58-.95s.67-2.97-.36-3.69");
}

.wj4kgr0on {
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.ygudl7bvr {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M82.19 46.1c3.7 0 7 4.02 7 10.76s-3.3 10.76-7 10.76s-7-4.02-7-10.76s3.3-10.66 7-10.76");
}

</style>
