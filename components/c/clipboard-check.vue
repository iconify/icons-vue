<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="et-47i68h"/><path class="znatxdbne"/><path clip-rule="evenodd" class="myu73bb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:clipboard-check" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.et-47i68h {
  fill-rule: evenodd;
  d: path("M5.675 2.5a1 1 0 0 1 1-1h6.643a1 1 0 0 1 1 1v3.875a1 1 0 0 1-1 1H6.675a1 1 0 0 1-1-1zm2 1v1.875h4.643V3.5z");
}

.myu73bb7u {
  fill-rule: evenodd;
  d: path("M12.567 8.677a1 1 0 0 1 .256 1.39l-1.767 2.565a1.5 1.5 0 0 1-2.154.334L7.387 11.79a1 1 0 0 1 1.226-1.58l1.097.851l1.467-2.128a1 1 0 0 1 1.39-.256");
}

.znatxdbne {
  d: path("M5 5v11h10V5h-1V3h2a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h2v2z");
}

</style>
