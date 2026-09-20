<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i-d2pn8kg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flash-checkmark-20-filled" /></template>
<style>
.i-d2pn8kg {
  fill: currentColor;
  d: path("M7.211 2c-.474 0-.891.314-1.021.77l-2.25 7.874a1.062 1.062 0 0 0 1.021 1.354H6.23l-1.17 4.68c-.264 1.055 1.04 1.777 1.795.995l2.22-2.267a5.5 5.5 0 0 1 6.22-6.35l.237-.24l.003-.005c.641-.667.18-1.811-.766-1.811h-2.564l1.261-3.594l.003-.008A1.062 1.062 0 0 0 12.46 2zM19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-2.146-1.854a.5.5 0 0 0-.708 0L13.5 15.293l-.646-.647a.5.5 0 0 0-.708.708l1 1a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0 0-.708");
}

</style>
