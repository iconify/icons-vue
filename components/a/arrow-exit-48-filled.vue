<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kqhf7rbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-exit-48-filled" /></template>
<style>
.kqhf7rbhz {
  fill: currentColor;
  d: path("M12.5 6A6.5 6.5 0 0 0 6 12.5v23a6.5 6.5 0 0 0 6.5 6.5h18a1.5 1.5 0 0 0 0-3h-18A3.5 3.5 0 0 1 9 35.5v-23A3.5 3.5 0 0 1 12.5 9h18a1.5 1.5 0 0 0 0-3zm22.56 8.44a1.5 1.5 0 0 0-2.12 2.12l5.939 5.94H17.5a1.5 1.5 0 0 0 0 3h21.379l-5.94 5.94a1.5 1.5 0 0 0 2.122 2.12l8.5-8.5a1.5 1.5 0 0 0 0-2.12z");
}

</style>
