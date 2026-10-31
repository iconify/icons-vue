<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cqz6y8_8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-48-regular" /></template>
<style>
.cqz6y8_8a {
  fill: currentColor;
  d: path("M17 16.5h-6.75a3.75 3.75 0 0 0-3.75 3.75v17.5a3.75 3.75 0 0 0 3.75 3.75h12.5a3.75 3.75 0 0 0 3.75-3.75V36H29v1.75A6.25 6.25 0 0 1 22.75 44h-12.5A6.25 6.25 0 0 1 4 37.75v-17.5A6.25 6.25 0 0 1 10.25 14H17zM37.75 4A6.25 6.25 0 0 1 44 10.25v17.5A6.25 6.25 0 0 1 37.75 34h-12.5A6.25 6.25 0 0 1 19 27.75v-17.5A6.25 6.25 0 0 1 25.25 4zm-12.5 2.5a3.75 3.75 0 0 0-3.75 3.75v17.5a3.75 3.75 0 0 0 3.75 3.75h12.5a3.75 3.75 0 0 0 3.75-3.75v-17.5a3.75 3.75 0 0 0-3.75-3.75z");
}

</style>
