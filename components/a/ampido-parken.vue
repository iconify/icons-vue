<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="edfk_-bzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ampido-parken" /></template>
<style>
.edfk_-bzq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.807 12.338l18.658-.004V31.3h-9.143v-9.576h-9.514l-.004-9.389M7.54 17.008l-.005 18.658h18.966v-9.143h-9.576v-9.514l-9.389-.004");
}

</style>
