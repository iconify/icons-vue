<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ow-v401sn"/><path class="lk572u7bp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-abandoned" /></template>
<style>
.lk572u7bp {
  d: path("M2.5 2.5h2L6.75 11m0 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7.383-.58q-.042-.102-.099-.196q-.058-.095-.128-.18t-.152-.158t-.173-.135t-.192-.108t-.205-.079t-.215-.048T12.75 13q-.074 0-.147.007t-.146.022q-.072.014-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126t-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146t-.007.147q0 .113.017.224q.017.112.05.219q.033.108.082.21q.05.101.113.194q.064.093.141.176t.165.152t.186.127q.098.056.203.096M16 16l5.5 5.5m0-5.5L16 21.5");
}

.ow-v401sn {
  d: path("M5 4.5h13.5L17 11H6.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
