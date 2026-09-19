<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lim0fi5id"/><path class="b2dltrbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dictionaryformids" /></template>
<style>
.b2dltrbmo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.73 4.5v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

.lim0fi5id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.96 28l-2.6-8l-2.7 8m.9-2.7h3.5m7.31-5.3h5.3l-5.3 8h5.3m-10.505-4h4M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2");
}

</style>
