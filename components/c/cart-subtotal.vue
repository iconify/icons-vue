<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zg108tb0g"/><path class="enyy2b2tv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cart-subtotal" /></template>
<style>
.enyy2b2tv {
  d: path("M5 6h15.5l-1.237 4.948M15.185 12H6m-1 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm7.954-.37q-.031-.12-.081-.234t-.118-.218t-.152-.195t-.182-.167t-.208-.136t-.226-.099t-.24-.061Q11.624 17 11.5 17q-.074 0-.147.007t-.146.022t-.142.036q-.071.021-.139.049t-.133.063t-.126.076q-.062.041-.119.087q-.057.047-.109.099t-.099.109q-.046.057-.087.119t-.076.126q-.035.065-.063.133t-.049.139q-.022.07-.036.142q-.015.073-.022.146T10 18.5t.007.147t.022.146q.014.072.036.142q.021.071.049.139t.063.133t.076.126q.041.062.087.119q.047.057.099.109t.109.099t.119.087t.126.076t.133.063t.139.049t.142.036q.073.015.146.022T11.5 20q.125 0 .249-.021q.123-.02.241-.061q.119-.041.229-.101q.109-.06.208-.138q.098-.077.183-.17q.084-.092.151-.197q.068-.106.118-.221t.078-.236m6.793-2.605C19.5 15.5 18.9 15 18 15c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M18 13.75V15m0 6v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zg108tb0g {
  d: path("M2.5 3h2l2 11.5H13");
}

</style>
