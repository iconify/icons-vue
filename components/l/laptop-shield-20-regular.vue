<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vdyre0l9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-shield-20-regular" /></template>
<style>
.vdyre0l9i {
  fill: currentColor;
  d: path("M15.12 9.963a.574.574 0 0 1 .76 0c.508.484 1.484 1.254 2.684 1.412c.239.031.436.212.436.438v2.11c0 2.839-2.784 3.87-3.386 4.06a.37.37 0 0 1-.227 0c-.602-.19-3.387-1.22-3.387-4.06v-2.11c0-.226.197-.407.437-.438c1.199-.158 2.174-.928 2.682-1.412M11.116 15c.08.362.198.695.345 1H2.5a.5.5 0 0 1 0-1zM15 5a2 2 0 0 1 2 2v2.606a6 6 0 0 1-.242-.196l-.187-.17l-.115-.1A1.5 1.5 0 0 0 16 8.898V7a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h6v.924l.003.076H5a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2z");
}

</style>
