<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myvrx-bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:link-multiple-24-regular" /></template>
<style>
.myvrx-bde {
  fill: currentColor;
  d: path("M6.25 4a5.25 5.25 0 0 0-1.703 10.218c.06-.51.181-1.002.353-1.468A3.751 3.751 0 0 1 6.25 5.5h6.5a3.75 3.75 0 1 1 0 7.5h-1a.75.75 0 0 0 0 1.5h1a5.25 5.25 0 1 0 0-10.5zm13.14 6.196c-.092.5-.243.98-.443 1.434A3.502 3.502 0 0 1 18 18.5h-7a3.5 3.5 0 1 1 0-7h1.25a.75.75 0 0 0 0-1.5H11a5 5 0 0 0 0 10h7a5 5 0 0 0 1.39-9.804");
}

</style>
