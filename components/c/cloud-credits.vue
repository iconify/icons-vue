<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vx7v9g0tp"/><path class="ze82kx64m"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cloud-credits" /></template>
<style>
.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vx7v9g0tp {
  d: path("M11.273 19H7q-.179-.049-.354-.111q-.174-.063-.344-.139t-.332-.165q-.163-.089-.318-.19q-.156-.102-.303-.215t-.284-.237q-.138-.125-.266-.26q-.127-.134-.244-.279q-.117-.144-.222-.297t-.198-.313q-.093-.161-.173-.328q-.08-.168-.147-.341t-.119-.351t-.092-.359t-.064-.366q-.025-.183-.035-.369q-.01-.185-.006-.371q.004-.185.023-.37q.018-.184.051-.367t.081-.362t.108-.355t.135-.345t.162-.334t.188-.319q.1-.157.212-.305t.235-.287t.256-.267q.134-.129.277-.247t.295-.225t.312-.2q.16-.095.327-.176q.166-.082.339-.15q.078-.228.174-.449t.21-.433t.243-.416q.131-.202.277-.394t.306-.371t.336-.345t.362-.317q.188-.152.387-.287q.199-.136.408-.256q.21-.119.428-.221t.444-.187q.225-.084.457-.15T11 6.06q.236-.047.475-.075q.24-.028.48-.037q.241-.009.482.002t.48.04q.239.03.475.078q.236.049.467.117q.231.067.456.153t.443.19t.426.224t.407.258t.384.29q.187.152.36.319q.174.167.334.348q.159.18.304.373q.145.192.274.396t.241.417t.206.435t.171.45t.135.462q.358.125.691.308t.63.419t.55.519q.254.282.456.603");
}

.ze82kx64m {
  d: path("M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
