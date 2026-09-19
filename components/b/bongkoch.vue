<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xc74v1eud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bongkoch" /></template>
<style>
.xc74v1eud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.42 16.955c2.684-3.918 6.362-7.741 10.574-12.455c4.29 4.8 8.026 8.677 10.723 12.672m1.713 19.796c1.664-2.415 2.833-5.346 2.638-8.49c-.268-4.323-2.018-7.85-4.351-11.305c-2.76 5.332-5.18 8.923-8.79 12.873c3.396 2.69 6.914 4.936 10.503 6.922A15.07 15.07 0 0 1 23.994 43.5c-8.322 0-15.381-6.732-15.074-15.022c.165-4.42 2.083-8 4.5-11.523c3.893 5.369 8.1 9.601 12.507 13.091");
}

</style>
