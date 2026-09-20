<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="h6ur5xamf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:blur-16-filled" /></template>
<style>
.h6ur5xamf {
  fill: currentColor;
  d: path("M8 2a6 6 0 1 0 4.472 10H8v-1h5.197q.275-.475.462-1H8V9h5.917Q14 8.511 14 8H8V7h5.917a6 6 0 0 0-.258-1H8V5h5.197a6 6 0 0 0-.725-1H8V3h3.318A5.97 5.97 0 0 0 8 2");
}

</style>
