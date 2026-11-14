<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wxro_lx3f"/><path class="atjzv5i0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:forex-order-ahead" /></template>
<style>
.atjzv5i0q {
  d: path("M11.724 16.244q-.23.012-.461-.001q-.23-.012-.457-.05q-.228-.038-.45-.1t-.436-.148t-.417-.194q-.204-.108-.394-.238t-.366-.279t-.334-.318q-.138-.146-.261-.304q-.124-.159-.232-.329q-.108-.169-.199-.348t-.166-.366t-.131-.38t-.094-.39t-.056-.398T7.251 12t.018-.401t.057-.398t.094-.39q.057-.193.131-.38t.166-.366t.199-.348t.232-.329q.123-.158.261-.304q.138-.147.289-.279t.314-.25t.337-.22t.355-.187t.372-.152q.189-.067.384-.117q.195-.049.394-.079q.198-.031.399-.043t.402-.004q.201.007.4.033t.395.071t.387.109t.375.144t.359.179t.341.212q.166.114.32.243M6 10.75h4.75M6 13.25h4.75M14.5 15h1.25l1 4h3.75l.75-2.75H16m1.25 5h.01m2.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wxro_lx3f {
  d: path("M13.2 19H2.5V5h19v8.4");
}

</style>
