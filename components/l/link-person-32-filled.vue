<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ss5f5zevf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-person-32-filled" /></template>
<style>
.ss5f5zevf {
  fill: currentColor;
  d: path("M9.25 6a7.25 7.25 0 0 0 0 14.5h3.5a1.25 1.25 0 1 0 0-2.5h-3.5a4.75 4.75 0 1 1 0-9.5h3.5a1.25 1.25 0 1 0 0-2.5zm13.5 0a7.25 7.25 0 0 1 5.974 11.359a5 5 0 0 0-1.597-2.26A4.75 4.75 0 0 0 22.75 8.5h-3.5a1.25 1.25 0 1 1 0-2.501zm.449 8.064a5 5 0 0 0-1.381.436H9.75a1.25 1.25 0 1 1 0-2.5h12.5a1.25 1.25 0 0 1 .949 2.064M27.5 19a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m2.5 7.438c0 2.023-1.714 4.062-6 4.062s-6-2.031-6-4.062C18 25.102 19.082 24 20.417 24h7.166C28.918 24 30 25.102 30 26.438");
}

</style>
