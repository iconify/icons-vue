<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="io053yswy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:game-controller-button-y-20-regular" /></template>
<style>
.io053yswy {
  fill: currentColor;
  d: path("M10 2a8 8 0 1 1 0 16a8 8 0 0 1 0-16m0 1a7 7 0 1 0 0 14a7 7 0 0 0 0-14m2.076 3.235a.5.5 0 1 1 .848.53L10.5 10.643V13.5a.5.5 0 0 1-1 0v-2.857L7.076 6.765a.5.5 0 1 1 .848-.53L10 9.557z");
}

</style>
