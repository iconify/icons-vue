<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ugsjkdbsv"/><path class="kwl_oubis"/><path class="k5kby07hl"/><path class="xtc4u0b1p"/><path class="hv8gehb8l"/><path class="qrvs2qgwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-guyana" /></template>
<style>
.hv8gehb8l {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M12.5 9.2c-1 .9-2 1.8-2.9 2.8l20 20l-20 20c.9 1 1.8 1.9 2.9 2.8L35.3 32z");
}

.k5kby07hl {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.5 8.4L62 31.8c0-1.6-.1-3.1-.4-4.6L17.4 5.8c-1.4.8-2.7 1.6-3.9 2.6");
}

.kwl_oubis {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M60.1 29.6L17.4 8v.4h-3.8c-.3.3-.7.5-1 .8v45.5c.3.3.7.6 1 .8h3.7v.5l43.2-21.5c.1-.8 1.6-1.7 1.6-2.5s-2-1.6-2-2.4");
}

.qrvs2qgwa {
  fill: var(--svg-color--fff, #fff);
  d: path("M61.6 36.8c.2-1.5.4-3.1.4-4.6L13.5 55.6c1.2 1 2.5 1.8 3.9 2.6z");
}

.ugsjkdbsv {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 2c-5.3 0-10.3 1.4-14.6 3.8l-.1 52.3C21.6 60.6 26.6 62 32 62c14.9 0 27.3-10.9 29.6-25.2v-9.6C59.3 12.9 46.9 2 32 2");
}

.xtc4u0b1p {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M12.5 12H9.6C4.9 17.3 2 24.3 2 32s2.9 14.7 7.6 20h2.8l20-20z");
}

</style>
