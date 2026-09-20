<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqbcfhb3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-48-regular" /></template>
<style>
.jqbcfhb3f {
  fill: currentColor;
  d: path("M38.75 8c.69 0 1.25.56 1.25 1.25v15.5a1.25 1.25 0 1 1-2.5 0V12.268L12.268 37.5H24.75a1.25 1.25 0 1 1 0 2.5H9.25C8.56 40 8 39.44 8 38.75v-15.5a1.25 1.25 0 1 1 2.5 0v12.482L35.732 10.5H23.25a1.25 1.25 0 1 1 0-2.5z");
}

</style>
