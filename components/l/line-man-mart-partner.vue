<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o-ssubb-l"/><path class="djp94-b2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:line-man-mart-partner" /></template>
<style>
.djp94-b2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.883 24.47L24 29.585l5.117-5.117m-9.901 3.39v7.331m9.568-7.331v7.331");
}

.o-ssubb-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 15.713h37c1.147 0 2.07.924 2.07 2.071v1.006c0 1.147-.923 2.07-2.07 2.07h-37a2.066 2.066 0 0 1-2.07-2.062v-1.014c0-1.147.923-2.07 2.07-2.07m.14 5.148l4.088 16.033c.361 1.415.754 2.474 2.475 2.474h23.594c1.721 0 2.114-1.06 2.475-2.474l4.088-16.033M16.475 8.631l-5.716 7.082m20.766-7.082l5.716 7.082");
}

</style>
