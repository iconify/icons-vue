<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v2cunjb9g"/><path class="schj8le8s"/><path class="ync-jn0hz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.schj8le8s {
  d: path("M13.9863 5L11.9995 12.4149L10.0127 19.8297");
}

.v2cunjb9g {
  d: path("M17 7.82959L18.6965 9.35641C20.239 10.7447 21.0103 11.4389 21.0103 12.3296C21.0103 13.2203 20.239 13.9145 18.6965 15.3028L17 16.8296");
}

.ync-jn0hz {
  d: path("M6.99956 7.82959L5.30309 9.35641C3.76054 10.7447 2.98926 11.4389 2.98926 12.3296C2.98926 13.2203 3.76054 13.9145 5.30309 15.3028L6.99956 16.8296");
}

</style>
