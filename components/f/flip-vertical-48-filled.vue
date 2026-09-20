<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uqakznpju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-48-filled" /></template>
<style>
.uqakznpju {
  fill: currentColor;
  d: path("M39.312 4.239A1.5 1.5 0 0 1 40 5.5v15a1.5 1.5 0 0 1-1.5 1.5h-33a1.5 1.5 0 0 1-.62-2.866l33-15a1.5 1.5 0 0 1 1.432.105M12.425 19H37V7.83zM40 43a1 1 0 0 1-1.425.905l-34-16A1 1 0 0 1 5 26h34a1 1 0 0 1 1 1z");
}

</style>
