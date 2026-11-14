<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9pli0bmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:acoustic-guitar" /></template>
<style>
.y9pli0bmn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.694 6.487q1.591-1.59 0-3.181t-3.181 0l-.707.707q-1.299 1.298-.477 2.597l-2.94 2.94Q11.957 8.514 10.113 9q-1.916.505-2.636 2.221q-1.901-.006-3.394 1.289q-1.724 1.498-1.805 3.78t1.535 3.897t3.897 1.535t3.78-1.805q1.295-1.493 1.289-3.394q1.716-.72 2.221-2.636q.486-1.844-.55-3.276l2.94-2.94q1.298.822 2.597-.477zM5.25 16.5q0-2.25 2.25-2.25t2.25 2.25t-2.25 2.25t-2.25-2.25");
}

</style>
