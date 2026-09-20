<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eyl-qi10d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:compose-48-regular" /></template>
<style>
.eyl-qi10d {
  fill: currentColor;
  d: path("M26.75 8a1.25 1.25 0 1 1 0 2.5h-14.5a3.75 3.75 0 0 0-3.75 3.75v21.5a3.75 3.75 0 0 0 3.75 3.75h21.5a3.75 3.75 0 0 0 3.75-3.75v-14.5a1.25 1.25 0 0 1 2.5 0v14.5A6.25 6.25 0 0 1 33.75 42h-21.5A6.25 6.25 0 0 1 6 35.75v-21.5A6.25 6.25 0 0 1 12.25 8zm13.116-1.634a1.25 1.25 0 1 1 1.768 1.768L21.65 28.116L19 29l.884-2.651z");
}

</style>
