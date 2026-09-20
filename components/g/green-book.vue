<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="cvbsnnbbd"/><path class="dt3bv-bbo"/><path class="e8gu7bmdi"/><path class="n3uochbzy"/><path class="zz8s06_4l"/><path class="y5wzmpb_p"/><path class="ddyzvnb3a"/><path class="f8b6a8d_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:green-book" /></template>
<style>
.cvbsnnbbd {
  fill: var(--svg-color--689f38, #689f38);
  d: path("M106.02 121.68H36.18c-1.66 0-1.26-1.35-1.26-3.01V14.05c0-1.66 1.35-3.01 3.01-3.01h69.36c2.72 0 4.93 2.21 4.93 4.93v99.76c0 3.86-1.83 5.95-6.2 5.95");
}

.ddyzvnb3a {
  fill: none;
  stroke: var(--svg-color--424242, #424242);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M23.18 6.45v104.4");
}

.dt3bv-bbo {
  fill: var(--svg-color--94c6d6, #94c6d6);
  d: path("M18.53 115.14c0 1.94 3.07 3.57 5.01 3.57l80.39-.05c2.98 0 4.54-1.58 4.54-3.52l-.25-21.32H18.53z");
}

.e8gu7bmdi {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
  d: path("M101.47 105.88s-2.13 5.85.03 8.78c2.51 3.4 6.89 2.58 6.89.99V16.44c0-.66-.61-1.14-1.25-1c-1.39.3-3.89.31-7.21-1.89z");
}

.f8b6a8d_w {
  fill: none;
  stroke: var(--svg-color--424242, #424242);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3px, 3px);
  d: path("m34.38 109.34l-11.3.22c-3.77 0-5.06 4.04-4.39 6.71c.84 3.37 4.32 3.92 5.18 3.92h12.65");
}

.n3uochbzy {
  fill: var(--svg-color--689f38, #689f38);
  d: path("M94.16 110.85H23.64V6.45h72.25c2.27 0 3.87.61 4.62 1.62c.98 1.31 1.5 3.3 1.5 5.48V103a7.85 7.85 0 0 1-7.85 7.85");
}

.y5wzmpb_p {
  fill: var(--svg-color--616161, #616161);
  d: path("M34.43 109.75L34.38 6.46h-11.2s-2.31-.4-3.85 0c-2.79.73-3.56 2.76-3.56 6.07v94.41c0 6.7.41 9.6 2.44 11.72c-.12-1.54.87-6.83 1.68-8.28c.72-1.28 14.54-.63 14.54-.63");
}

.zz8s06_4l {
  fill: var(--svg-color--9ccc65, #9ccc65);
  d: path("M92.01 107.78H25.54c-2.76 0-4.99-2.24-4.99-4.99V11.45c0-2.76 2.24-4.99 4.99-4.99h66.47c3.82 0 6.92 2.18 6.92 6.92v87.49c-.01 3.81-3.1 6.91-6.92 6.91");
}

</style>
