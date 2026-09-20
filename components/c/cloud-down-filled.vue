<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="r-pirlb1i"/><path class="ci9fsyyqx"/><path class="meco3rogb"/><path class="s29ll1g5q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:cloud-down-filled" /></template>
<style>
.ci9fsyyqx {
  d: path("M9.5 9.5a1 1 0 1 1 2 0V17a1 1 0 1 1-2 0V9.5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.meco3rogb {
  d: path("M12.375 14.72a1 1 0 1 1 1.25 1.56l-2.5 2a1 1 0 0 1-1.25-1.56l2.5-2Z");
}

.r-pirlb1i {
  fill-rule: evenodd;
  d: path("M12 14V9.25a1.5 1.5 0 0 0-3 0V14H6a4 4 0 0 1 0-8h.126C6.57 4.275 8.136 3 10 3h1c1.9 0 3.49 1.325 3.899 3.101A4.002 4.002 0 0 1 14 14h-2Z");
}

.s29ll1g5q {
  d: path("M7.375 16.28a1 1 0 1 1 1.25-1.56l2.5 2a1 1 0 0 1-1.25 1.56l-2.5-2Z");
}

</style>
