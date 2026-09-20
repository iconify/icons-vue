<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jb-giebgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-checkmark-20-regular" /></template>
<style>
.jb-giebgh {
  fill: currentColor;
  d: path("M4.5 9a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m2.354 2.646a.5.5 0 0 0-.708 0L3.5 14.294l-.646-.646a.5.5 0 1 0-.708.707l1 1a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0 0-.707M16 5a3 3 0 0 1 3 3a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1a3 3 0 0 1-3 3H9.792q.137-.483.185-1H16a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2H3a2 2 0 0 0-2 2v1.257a5.5 5.5 0 0 0-1 1.082V8a3 3 0 0 1 3-3z");
}

</style>
