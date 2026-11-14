<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="udxq1wbzz"/><path class="vi1vaabuj"/><path class="v9fx87bkk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-chat" /></template>
<style>
.udxq1wbzz {
  d: path("M4.5 2.5h15a2 2 0 0 1 2 2v11a2 2 0 0 1-2 2H10L6 21v-3.5H4.5a2 2 0 0 1-2-2v-11a2 2 0 0 1 2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9fx87bkk {
  d: path("M12.75 5.25v2h2");
}

.vi1vaabuj {
  d: path("M9.25 5.25h3.5l2 2v7.5h-5.5Z");
}

</style>
