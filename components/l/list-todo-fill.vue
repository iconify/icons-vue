<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4olpwcff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-todo-fill" /></template>
<style>
.z4olpwcff {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Zm2 0v4h4V5Zm9 1h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2M3.707 16.293L5 17.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-2-2a.999.999 0 1 1 1.414-1.414M13 16h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
