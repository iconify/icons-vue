<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="lxrvnfbih"/><path class="wgqjg7biy"/><path class="mfoopacwf"/><path class="uygxwmbrl"/><path class="ie1747bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:candle" /></template>
<style>
.ie1747bnj {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M11 29a1 1 0 1 1-2 0v-7a1 1 0 1 1 2 0zm4 3a1 1 0 1 1-2 0v-7a1 1 0 1 1 2 0zm0-11a1 1 0 1 1-2 0v-1a1 1 0 1 1 2 0z");
}

.lxrvnfbih {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M20 21.5a1.5 1.5 0 0 1-3 0v-3a1.5 1.5 0 1 1 3 0z");
}

.mfoopacwf {
  fill: var(--svg-color--fcab40, #fcab40);
  d: path("M18.687 18.538c-2.595 0-6.962-1.934-6.962-5.898c0-3.988 4.351-5.414 7.005-11.401c.751-1.693.999-1.107 1.86-.076c2.06 2.463 5.058 7.483 5.058 11.574c-.001 4.641-4.64 5.801-6.961 5.801");
}

.uygxwmbrl {
  fill: var(--svg-color--fdcb58, #fdcb58);
  d: path("M18.687 17.447c-4.184 0-3.482-5.802 0-9.283c2.321 1.16 5.801 9.283 0 9.283");
}

.wgqjg7biy {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M27.138 33.817C27.183 35.022 26.206 36 25 36H12.183A2.183 2.183 0 0 1 10 33.817V21c0-1.205.115-2.183 2.183-2.183S15 23 25 21c1.091 0 2.183.978 2.138 2.183z");
}

</style>
