<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rvy1sbcos"/><path class="su9clsbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carrier-unlock" /></template>
<style>
.rvy1sbcos {
  d: path("M12.164 20H4V2.5h9.5L18 7v4.936");
}

.su9clsbyh {
  d: path("M7 7.5h6.5V14H7Zm8 10h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3-.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
