<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jjscs_bwa"/><path class="yea5zkk6n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:automation-error" /></template>
<style>
.jjscs_bwa {
  d: path("m9.237 4.634l.198-2.063h2.13l.198 2.063l1.992.825l1.598-1.319l1.507 1.507l-1.319 1.598l.825 1.992l2.063.198v2.13l-2.063.198l-.825 1.992l1.319 1.598l-1.507 1.507l-1.598-1.319l-1.992.825l-.198 2.063h-2.13l-.198-2.063l-1.992-.825l-1.598 1.319l-1.507-1.507l1.319-1.598l-.825-1.992l-2.063-.198v-2.13l2.063-.198l.825-1.992L4.14 5.647L5.647 4.14l1.598 1.319Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yea5zkk6n {
  d: path("M7.75 10.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM20 15v3.25M20 21h.01");
}

</style>
