<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="k7vl1bbrp"/><path class="lu1e5s_3v"/><path class="e8lrys2nv"/><path class="efn1muemv"/><path class="lmu6jyghu"/><path class="m_z2ykb_r"/><path class="p4dr31xxr"/><ellipse class="alps88tbz"/><path class="re7y-_bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:light-rail" /></template>
<style>
.alps88tbz {
  cx: 6.4px;
  cy: 52.8px;
  fill: var(--svg-color--fff, #fff);
  rx: 0.7px;
  ry: 2.2px;
}

.e8lrys2nv {
  fill: var(--svg-color--dfecf4, #dfecf4);
  d: path("M25.3 14C14.5 14 2 37.4 2 50.6c0 3.2 2.5 5.8 5.7 5.9H62V14z");
}

.efn1muemv {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M15.1 19.9c-6.8 7.4-12.5 20.2-13 29.2h10.2s13.2 0 13.2-7.3v-22zm26.4 0c-7.3 0-7.3 1.5-7.3 15.4v13.9H62V19.9z");
}

.k7vl1bbrp {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M2 56.5h60V62H2z");
}

.lmu6jyghu {
  fill: var(--svg-color--3baacf, #3baacf);
  d: path("M2.1 49.1c0 .5-.1 1-.1 1.5c0 3.2 2.5 5.8 5.7 5.9H62v-7.3z");
}

.lu1e5s_3v {
  fill: var(--svg-color--62696d, #62696d);
  d: path("M2 56.5h60v1.8H2z");
}

.m_z2ykb_r {
  fill: var(--svg-color--fdf516, #fdf516);
  d: path("M11.5 56.5s7.3-7.3 22-7.3H62v7.3z");
}

.p4dr31xxr {
  fill: var(--svg-color--62696d, #62696d);
  d: path("M47.4 34.5c-.8 0-1.3.7-1.5 1.5l-1.3 10.2H40c-1.4 0-1.4.9-1.4 2v1h10.3V34.5zm13.1 0c-.8 0-1.3.7-1.5 1.5l-1.3 10.2H53c-1.4 0-1.4.9-1.4 2v1H62V34.5z");
}

.re7y-_bgs {
  fill: var(--svg-color--3baacf, #3baacf);
  d: path("M25.4 56.5s11.3-7.3 24.6-7.3c0 0 11.9 0 11.9-11.1v18.4z");
}

</style>
