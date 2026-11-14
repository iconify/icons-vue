<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j38wngbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kite-control-bar" /></template>
<style>
.j38wngbdm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.548 15.25q2.702.024 2.702 2.75q0 2.75-2.75 2.75h-1q-2.345 0-2.69-2H8.19q-.345 2-2.69 2h-1q-2.75 0-2.75-2.75q0-1.139.805-1.945q.789-.788 1.897-.805L8.286 3.271q.045-.142.142-.256q.096-.113.229-.182q.132-.068.281-.08q.148-.013.291.033q.07.022.135.058q.064.036.121.084q.056.047.102.105t.08.124q.034.065.054.136t.026.145t-.002.147t-.031.144L6.019 15.277q1.866.206 2.171 1.973h7.62q.305-1.767 2.171-1.973L14.286 3.729q-.023-.071-.031-.144q-.009-.074-.002-.147q.006-.074.026-.145t.054-.136t.08-.124q.046-.058.102-.105q.057-.048.121-.084q.065-.036.135-.058q.143-.046.291-.033q.149.012.281.08q.133.069.229.182q.097.114.142.256z");
}

</style>
