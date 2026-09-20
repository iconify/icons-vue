<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yd44w6bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-down-right-48-filled" /></template>
<style>
.yd44w6bte {
  fill: currentColor;
  d: path("M13 7.5a1.5 1.5 0 0 0-3 0v18a7.5 7.5 0 0 0 7.5 7.5h17.379l-6.44 6.44a1.5 1.5 0 0 0 2.122 2.12l9-9a1.5 1.5 0 0 0 0-2.12l-9-9a1.5 1.5 0 0 0-2.122 2.12L34.88 30H17.5a4.5 4.5 0 0 1-4.5-4.5z");
}

</style>
