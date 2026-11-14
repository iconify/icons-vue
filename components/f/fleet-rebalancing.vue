<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tmpf6lb4t"/><path class="ne2-ldb_j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fleet-rebalancing" /></template>
<style>
.ne2-ldb_j {
  d: path("m5.5 12l3-5.5h6L17 12M5.5 12H11l3.5-5.5m-6 0l-.5-2m-1.5 0h3m5 2l.5-2h2m-2 11.75h6m-1.75-1.75L21 16.25m0 3.5h-6m1.75 1.75L15 19.75");
}

.tmpf6lb4t {
  d: path("M2 12a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm18.496-.172q-.008-.167-.032-.332q-.024-.164-.064-.326q-.039-.162-.094-.319q-.055-.158-.124-.309q-.07-.151-.153-.296q-.083-.144-.18-.279t-.206-.262q-.109-.125-.23-.24q-.12-.115-.251-.218t-.272-.193t-.288-.166t-.303-.138q-.154-.062-.314-.109q-.16-.046-.323-.078q-.164-.031-.33-.047Q17.167 8.5 17 8.5q-.172 0-.343.017t-.34.05q-.168.034-.333.084t-.323.115q-.159.066-.311.147t-.294.177t-.276.204q-.133.11-.255.231q-.121.122-.231.255q-.109.133-.204.276q-.096.142-.177.294t-.147.311q-.065.158-.115.323t-.084.333q-.033.169-.05.34T13.5 12q0 .755.311 1.443");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
