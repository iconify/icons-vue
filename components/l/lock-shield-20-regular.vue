<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ld90xs3uw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-shield-20-regular" /></template>
<style>
.ld90xs3uw {
  fill: currentColor;
  d: path("M15.12 10.963a.574.574 0 0 1 .76 0c.508.484 1.484 1.254 2.684 1.412c.239.031.436.212.436.438v2.11c0 2.839-2.784 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.174-.928 2.682-1.412M10 1a4 4 0 0 1 4 4v2.05a2.5 2.5 0 0 1 2 2.45v.397a1.6 1.6 0 0 0-1 0V9.5A1.5 1.5 0 0 0 13.5 8h-7A1.5 1.5 0 0 0 5 9.5v6A1.5 1.5 0 0 0 6.5 17h4.962c.18.375.402.707.646 1H6.5A2.5 2.5 0 0 1 4 15.5v-6a2.5 2.5 0 0 1 2-2.45V5a4 4 0 0 1 4-4m0 10.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2M10 2a3 3 0 0 0-3 3v2h6V5a3 3 0 0 0-3-3");
}

</style>
