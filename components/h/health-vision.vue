<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hieahobel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:health-vision" /></template>
<style>
.hieahobel {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.008 12.889l.75-5q.011-.073.036-.143t.063-.133t.088-.118t.109-.098t.126-.076q.067-.031.139-.049t.145-.021t.147.007q.148.022.276.099q.127.077.216.197t.125.265t.014.292l-.33 2.2Q5.038 9.5 6.5 9.5q1.864 0 3.182 1.318q1.045 1.045 1.261 2.432h2.114q.216-1.387 1.261-2.432Q15.636 9.5 17.5 9.5q1.462 0 2.588.811l-.33-2.2q-.022-.147.014-.292t.125-.265t.216-.197q.128-.077.276-.099q.073-.011.147-.007q.073.003.145.021t.139.049q.066.032.126.076q.059.044.109.098t.088.118t.063.133q.025.07.036.143l.75 5q.03.199-.045.387q.053.351.053.724q0 1.864-1.318 3.182T17.5 18.5t-3.182-1.318q-1.045-1.045-1.261-2.432h-2.114q-.216 1.387-1.261 2.432Q8.364 18.5 6.5 18.5t-3.182-1.318T2 14q0-.373.053-.724q-.075-.188-.045-.387");
}

</style>
