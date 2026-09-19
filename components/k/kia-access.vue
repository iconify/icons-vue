<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="muu8vfw-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kia-access" /></template>
<style>
.muu8vfw-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.972 9.588a20.42 20.42 0 0 1 10.48 8.444M26.181 4.5a25.04 25.04 0 0 1 16.38 13.167m-22.428-3.555c-8.115 0-14.694 6.579-14.694 14.694S12.018 43.5 20.133 43.5c.834 0 1.65-.075 2.446-.208v-8.304a6.648 6.648 0 1 1 4.202-6.183v14.629l8.046.066V28.806c0-8.115-6.579-14.694-14.694-14.694");
}

</style>
