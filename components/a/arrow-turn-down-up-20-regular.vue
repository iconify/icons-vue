<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rou96ac-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-down-up-20-regular" /></template>
<style>
.rou96ac-f {
  fill: currentColor;
  d: path("M15.566 3.004a.5.5 0 0 1 .4.31l1.998 5a.5.5 0 1 1-.928.372L15.5 4.848l-4.59 11.524c-.329.828-1.495.844-1.847.025L4.04 4.697a.5.5 0 0 1 .919-.394l5.023 11.7L14.55 4.534l-3.826 1.912a.5.5 0 1 1-.447-.894l4.982-2.49a.5.5 0 0 1 .307-.059");
}

</style>
