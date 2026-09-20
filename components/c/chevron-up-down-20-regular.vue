<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b6q56nb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-up-down-20-regular" /></template>
<style>
.b6q56nb9h {
  fill: currentColor;
  d: path("M14.911 7.216a.5.5 0 0 1-.765.638L10 3.707L5.854 7.854l-.07.057a.5.5 0 0 1-.638-.765l4.5-4.5l.07-.057a.5.5 0 0 1 .638.057l4.5 4.5zM5.09 12.784a.5.5 0 0 1 .765-.638L10 16.293l4.146-4.147l.07-.057a.5.5 0 0 1 .638.765l-4.5 4.5l-.07.057a.5.5 0 0 1-.638-.057l-4.5-4.5z");
}

</style>
