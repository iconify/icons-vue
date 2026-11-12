<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="trr-_mkon"/><circle class="dos_yhbgg"/><circle class="ez1x61b2a"/><path class="qu29-jloa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bicycling-broken" /></template>
<style>
.dos_yhbgg {
  cx: 6px;
  cy: 18px;
  r: 3px;
}

.ez1x61b2a {
  cx: 18px;
  cy: 18px;
  r: 3px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qu29-jloa {
  d: path("M18.5 10H16.4744C15.2534 10 14.6429 10 14.0934 9.77341C13.544 9.54682 13.111 9.11646 12.2449 8.25573L11.6676 7.68194C10.8828 6.90201 10.4904 6.51204 10.0257 6.55439C9.56102 6.59673 9.24559 7.0512 8.61471 7.96013M12 18L12.0572 17.6416C12.2918 16.172 12.4091 15.4373 12.081 14.8374C11.7529 14.2375 11.0709 13.9399 9.70695 13.3448L8.23125 12.7009C7.1987 12.2503 6.68242 12.025 6.55348 11.5703C6.50262 11.3909 6.5218 11.2103 6.60313 11.0005");
}

.trr-_mkon {
  cx: 15px;
  cy: 4px;
  r: 2px;
}

</style>
