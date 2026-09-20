<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ivzge5bet"/><path class="t0-3spbof"/><path class="ytw31uban"/><path class="bmz5xl9sb"/><path class="bgzpu_b2c"/><path class="uhm6p217g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:foom" /></template>
<style>
.bgzpu_b2c {
  fill: var(--svg-color--red, red);
  d: path("M9.188 8.628h6.75l-.619.843h-4.443v1.406h4.865l-.742.844h-4.123v2.531H9.188z");
}

.bmz5xl9sb {
  fill: var(--svg-color--00f8ff, #00f8ff);
  d: path("M8.063 9.75h6.75l-.619.844H9.751V12h4.865l-.742.844H9.75v2.531H8.063z");
}

.ft5dv1b6b {
  fill: none;
}

.ivzge5bet {
  fill: var(--svg-color--red, red);
  d: path("M5.813 3.563H21v15.186H5.813z");
}

.t0-3spbof {
  fill: var(--svg-color--00f8ff, #00f8ff);
  d: path("M3 5.813h15.749v14.624H3z");
}

.uhm6p217g {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.625 9.188h6.75l-.62.844h-4.443v1.406h4.866l-.743.844h-4.123v2.53H8.625z");
}

.ytw31uban {
  fill: var(--svg-color--000, #000);
  d: path("M4.126 4.69h15.749v14.624H4.126z");
}

</style>
