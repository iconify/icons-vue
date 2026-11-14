<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoi06dhqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:flash-on" /></template>
<style>
.yoi06dhqc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.726 4.837q.907-.946 2.028-.269q1.122.676.708 1.919l-.592 1.776q-.122.364.103.676q.224.311.608.311h1.909q1.485.001 2.069 1.367q.583 1.365-.444 2.438l-5.841 6.108q-.907.946-2.028.269q-1.122-.676-.708-1.919l.592-1.776q.122-.364-.103-.676q-.224-.311-.608-.311H7.51q-1.485-.001-2.069-1.367q-.583-1.365.444-2.438z");
}

</style>
