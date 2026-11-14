<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utk4h9xqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-left-right" /></template>
<style>
.utk4h9xqd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.368 13.718q-.796-.675-.796-1.718t.797-1.718l2.678-2.266q1.096-.928 2.4-.323q1.303.604 1.303 2.041v4.532q0 1.437-1.303 2.041q-1.304.605-2.4-.323zm12.585 2.266l2.678-2.266h.001q.796-.675.796-1.718t-.797-1.718l-2.677-2.266q-1.097-.928-2.401-.323q-1.303.604-1.303 2.041v4.532q0 1.437 1.303 2.041q1.304.605 2.4-.323");
}

</style>
