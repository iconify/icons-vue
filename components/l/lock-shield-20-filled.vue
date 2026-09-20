<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cfe9chbpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-20-filled" /></template>
<style>
.cfe9chbpu {
  fill: currentColor;
  d: path("M15.12 10.963a.574.574 0 0 1 .76 0c.508.484 1.484 1.254 2.684 1.412c.239.031.436.212.436.438v2.11c0 2.839-2.784 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.174-.928 2.682-1.412M10 1a4 4 0 0 1 4 4v2.05a2.5 2.5 0 0 1 2 2.45v.397a1.58 1.58 0 0 0-1.456.244l-.115.098c-.432.412-1.147.955-1.96 1.117l-.269.045c-.531.112-1.116.54-1.192 1.254l-.008.157v2.112A4.7 4.7 0 0 0 12.108 18H6.5A2.5 2.5 0 0 1 4 15.5v-6a2.5 2.5 0 0 1 2-2.45V5a4 4 0 0 1 4-4m0 10.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2M10 2a3 3 0 0 0-3 3v2h6V5a3 3 0 0 0-3-3");
}

</style>
