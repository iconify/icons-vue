<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="znalogb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-shield-16-regular" /></template>
<style>
.znalogb3r {
  fill: currentColor;
  d: path("M11.12 6.963a.574.574 0 0 1 .76 0c.508.484 1.484 1.254 2.683 1.412c.24.031.437.212.437.438v2.11c0 2.839-2.784 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.174-.928 2.682-1.412M7.002 11q.009.534.114 1H2.5a.5.5 0 0 1 0-1zM11.5 3A1.5 1.5 0 0 1 13 4.5v2.106a6 6 0 0 1-.242-.196l-.187-.17l-.115-.1A1.5 1.5 0 0 0 12 5.898V4.5a.5.5 0 0 0-.5-.5h-7a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 .5.5H7v1H4.5A1.5 1.5 0 0 1 3 8.5v-4A1.5 1.5 0 0 1 4.5 3z");
}

</style>
