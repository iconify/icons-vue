<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wo1e-3bju"/><path class="yfz58os1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charity-ball" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wo1e-3bju {
  d: path("M13.314 14.358c-.486-.444-.9-.944-1.314-1.358c-1 1-2 2.5-4 2.5c-3 0-5.5-4-5.5-10c4-1 7 0 9.5 1.5c2.5-1.5 5.5-2.5 9.5-1.5c0 2.933-.597 5.388-1.559 7.132");
}

.yfz58os1c {
  d: path("M5.5 9.75a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0m9 0a2 1.5 0 1 0 4 0a2 1.5 0 1 0-4 0m3.764 5.292l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

</style>
