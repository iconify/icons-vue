<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7xjiovbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-spoon" /></template>
<style>
.t7xjiovbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.486 12.463C28.486 8.618 26.478 5.5 24 5.5s-4.486 3.118-4.486 6.963c0 3.572 1.042 6.514 3.274 6.914h0l-.623 21.602c0 .84.688 1.521 1.538 1.521s1.538-.68 1.538-1.52l-.022-21.607h0c2.229-.407 3.267-3.342 3.267-6.91");
}

</style>
