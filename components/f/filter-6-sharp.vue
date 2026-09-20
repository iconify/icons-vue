<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu5efhbus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:filter-6-sharp" /></template>
<style>
.yu5efhbus {
  fill: currentColor;
  d: path("M12 9.5v-3h3v-1h-4v9h5v-5zm0 1h3v3h-3zM6.5 17V3h14v14zm-3 3V6.616h1V19h12.385v1z");
}

</style>
