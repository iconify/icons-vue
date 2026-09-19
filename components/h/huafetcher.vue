<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="scfsvuyqo"/><path class="kya0kebzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huafetcher" /></template>
<style>
.kya0kebzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.62 12.645l-.931-6.431a2 2 0 0 0-1.98-1.714h-9.757a2 2 0 0 0-1.98 1.714l-.93 6.431m0 22.71l.931 6.432a2 2 0 0 0 1.98 1.713h9.757a2 2 0 0 0 1.98-1.713l.93-6.432M17.407 18.451v11.098m0-4.578a2.775 2.775 0 0 1 2.774-2.774h0a2.775 2.775 0 0 1 2.775 2.774v4.578m3.734 0v-9.156c0-1.073.869-1.942 1.942-1.942h0c.956 0 1.552.283 1.961.812m-5.549 2.934h3.885");
}

.scfsvuyqo {
  cx: 23.831px;
  cy: 24px;
  r: 13.771px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
