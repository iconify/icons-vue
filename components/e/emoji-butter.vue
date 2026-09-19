<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r7li8lbrl"/><path class="jbu-uub3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-butter" /></template>
<style>
.jbu-uub3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 30.8H11.516a1.46 1.46 0 0 1-1.082-.345l-.142-.14l-2.338-4.739l-2.454-.01M24 30.8h12.484c.393.036.783-.088 1.082-.345l.142-.14l2.339-4.738l2.453-.012M9.364 28.434H24m14.636 0H24");
}

.r7li8lbrl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.894 17.194a2.03 2.03 0 0 0-1.97 1.765l-.816 7.71a1.57 1.57 0 0 0 1.597 1.765h22.59a1.572 1.572 0 0 0 1.597-1.765l-.816-7.71a2.03 2.03 0 0 0-1.97-1.765z");
}

</style>
