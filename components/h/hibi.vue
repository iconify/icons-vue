<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qr8-0qbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hibi" /></template>
<style>
.qr8-0qbxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.439 33.963c1.711.985 3.394 2.272 4.575 3.614m-1.844-1.951c1.782-1.476 2.75-3.015 3.19-4.35c.141-.428-.036-.775-.403-.775H29.89m-3.424 2.931c1.634-.919 3.901-3.243 4.471-5.147m-4.092-12.443H35.5M27.473 10.5h7.399c.348 0 .628.28.628.628v9.699c0 .348-.28.628-.628.628h-7.399a.627.627 0 0 1-.628-.628v-9.699c0-.348.28-.628.628-.628m8.027-6h-23a4 4 0 0 0-4 4v31a4 4 0 0 0 4 4h23a4 4 0 0 0 4-4v-31a4 4 0 0 0-4-4M12.723 9.245v13.851l4.426-3.362l4.426 3.362V9.245z");
}

</style>
