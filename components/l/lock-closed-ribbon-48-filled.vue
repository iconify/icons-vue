<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wznygccss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-ribbon-48-filled" /></template>
<style>
.wznygccss {
  fill: currentColor;
  d: path("M42 45.996a1 1 0 0 1-1.588.809L36.5 43.96l-3.912 2.845A1 1 0 0 1 31 45.996v-5.749A9.46 9.46 0 0 0 36.5 42c2.05 0 3.948-.649 5.5-1.753zM24 4a9 9 0 0 1 9 9v5.006a6.25 6.25 0 0 1 5.93 5.308A9.5 9.5 0 0 0 27 32.5a9.46 9.46 0 0 0 2 5.832V44H15.25A6.25 6.25 0 0 1 9 37.75v-13.5a6.25 6.25 0 0 1 6-6.244V13a9 9 0 0 1 9-9m12.5 21a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M24 28.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5m0-22a6.5 6.5 0 0 0-6.5 6.5v5h13v-5A6.5 6.5 0 0 0 24 6.5");
}

</style>
