<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t-nm4bb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-down-48-filled" /></template>
<style>
.t-nm4bb7c {
  fill: currentColor;
  d: path("M7.5 13a1.5 1.5 0 0 1 0-3h18a7.5 7.5 0 0 1 7.5 7.5v17.379l6.44-6.44a1.5 1.5 0 0 1 2.12 2.122l-9 9a1.5 1.5 0 0 1-2.12 0l-9-9a1.5 1.5 0 0 1 2.12-2.122L30 34.88V17.5a4.5 4.5 0 0 0-4.5-4.5z");
}

</style>
