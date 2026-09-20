<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g1v8jeezh"/><circle class="l0u_imssf"/><path class="yljoyybif"/><circle class="xrl9ndraz"/><path class="wh7otmbpi"/><path class="s5-mt4bhu"/><ellipse transform="rotate(-63.294 104.412 39.164)" class="swmbggb2p"/><ellipse transform="rotate(-55.82 103.867 40.167)" class="v9kx23t_i"/><circle class="g2kxwx40a"/><path class="au2v2qb1a"/><path class="a6zi-hbkc"/><ellipse transform="rotate(-12.286 30.205 75.172)" class="y6_-ljb4j"/><ellipse transform="rotate(-12.286 31.428 75.71)" class="mzr_6hcsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:blueberries" /></template>
<style>
.a6zi-hbkc {
  fill: var(--svg-color--9aa7ed, #9aa7ed);
  d: path("M35.42 81.76s-4.05 7.91-11.4 5.77c-3.4-.99-1.81-6.31-1.81-6.31s-4.75-.39-6.47-4.48c-1.54-3.66 6.7-5.12 6.7-5.12s-3.26-6 .19-8.42s7.21 3.02 7.21 3.02s3.07-8.86 7.06-5.93c3.82 2.81 2.85 10.91 2.85 10.91s6.88 1.16 4.56 5.81c-2.56 5.12-8.89 4.75-8.89 4.75");
}

.au2v2qb1a {
  fill: var(--svg-color--5366cf, #5366cf);
  d: path("M70.98 77.09c.19 1.32.67 35.28-33.79 36.26c-14.12.4-23.69-8.91-28.13-19.59C4.5 82.79 9.9 69.8 9.9 69.8s-2.89 4.66-3.53 7.29c-1.21 3.5-1.87 7.25-1.87 11.15c0 18.88 15.3 34.18 34.18 34.18s34.18-15.3 34.18-34.18c-.01-3.91-.68-7.66-1.88-11.15");
}

.g1v8jeezh {
  fill: var(--svg-color--3f51b5, #3f51b5);
  d: path("M21.1 23.79c-.46.11-2.08-1.23-7.01-.76c-1.87.18-2.55.66-2.55.66s.18-2.66 2.42-4.45c1.57-1.26 3.01-1.75 4-1.94c.71-.14 1.16-.81 1.05-1.53c-.27-1.71-.32-4.52 1.83-5.95c2.02-1.35 4.19-.42 5.52.46c.66.44 1.54.23 1.92-.48c.5-.94 1.33-2.17 2.62-3.17c2.51-1.94 4.85-.62 4.85-.62s-2.15 1.86-2.25 6.6c-.01.52.19 1.82-.09 2.28c-3.28 2.33-5.38 4.13-8.66 6.47c-1.37.98-1.75 1.24-3.14 2.19c-.18.13-.35.2-.51.24");
}

.g2kxwx40a {
  cx: 38.67px;
  cy: 88.24px;
  r: 34.18px;
  fill: var(--svg-color--6678d9, #6678d9);
}

.l0u_imssf {
  cx: 43.83px;
  cy: 39.44px;
  r: 30.22px;
  fill: var(--svg-color--3f51b5, #3f51b5);
}

.mzr_6hcsv {
  cx: 31.42px;
  cy: 75.7px;
  fill: var(--svg-color--5366cf, #5366cf);
  rx: 6.57px;
  ry: 6.3px;
}

.s5-mt4bhu {
  fill: var(--svg-color--8092f2, #8092f2);
  d: path("M100.36 46.17s3.48 8 9.12 6.08c3.38-1.15 2.5-6.79 2.5-6.79s8.99-.41 8.58-4.36c-.42-4.05-6.07-5.37-6.07-5.37s-.49-5.85-2.51-7.4c-3.37-2.57-7.56 1.42-7.56 1.42s-3.23-5.41-8.11-4.36c-3.91.84-1.77 9.2-1.77 9.2s-5.66-.07-3.31 4.58c2.57 5.1 9.13 7 9.13 7");
}

.swmbggb2p {
  cx: 104.42px;
  cy: 39.16px;
  fill: var(--svg-color--2f3e82, #2f3e82);
  rx: 6.45px;
  ry: 7.34px;
}

.v9kx23t_i {
  cx: 103.87px;
  cy: 40.17px;
  fill: var(--svg-color--5064c9, #5064c9);
  rx: 5.52px;
  ry: 6.36px;
}

.wh7otmbpi {
  fill: var(--svg-color--4054b0, #4054b0);
  d: path("M123.47 61.06c-5.69 14.41-18.79 25.92-39.19 19.6c-16.67-5.17-25.41-25-20.49-40.55a33 33 0 0 0-4.83 9.49c-5.56 17.42 4.02 36.05 21.41 41.6s36-4.07 41.56-21.49c.91-2.87 1.41-5.77 1.54-8.65");
}

.xrl9ndraz {
  cx: 90.39px;
  cy: 59.75px;
  r: 33.12px;
  fill: var(--svg-color--5064c9, #5064c9);
}

.y6_-ljb4j {
  cx: 30.2px;
  cy: 75.16px;
  fill: var(--svg-color--2c3f9e, #2c3f9e);
  rx: 7.77px;
  ry: 7.17px;
}

.yljoyybif {
  fill: var(--svg-color--303f9f, #303f9f);
  d: path("M61.17 14.69c1.58 3.03 4.1 5.07 2.28 14.8c-1.41 7.54-7.71 15.42-20.65 16.26c-11.01.71-18.79-5.3-21.02-12.6c-2.12-6.94-.87-12.82 3.53-17.6c-11.22 7.48-11.7 20.41-11.7 23.88c0 16.69 13.53 30.22 30.22 30.22s30.22-13.53 30.22-30.22c.01-10.23-5.09-19.28-12.88-24.74");
}

</style>
