<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="leby7rq0j"/><path class="ry2xuwb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-scan-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.leby7rq0j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 3.8871V3C2 2.4477 2.4477 2 3 2H21C21.5523 2 22 2.4477 22 3V3.8871C22 4.3151 21.7276 4.6957 21.3225 4.8337L12.3139 7.9029L12.1697 7.9651C12.0817 8.0115 11.9183 8.0115 11.8303 7.9651L11.6861 7.9029L2.6775 4.8337C2.2724 4.6957 2 4.3151 2 3.8871ZM2 8.1129C2 7.7903 2.1556 7.4875 2.418 7.2997C2.6803 7.112 3.0171 7.0623 3.3225 7.1663L10.978 9.7746C11.6111 10.0756 12.3889 10.0756 13.022 9.7746L20.6775 7.1663C20.9829 7.0623 21.3197 7.112 21.582 7.2997C21.8444 7.4875 22 7.7903 22 8.1129V12H23V14H1V12H2Z");
  stroke: none;
}

.ry2xuwb7e {
  d: path("M2 17H11M22 17H13M21 21H17M15 21H9M7 21H3");
}

</style>
