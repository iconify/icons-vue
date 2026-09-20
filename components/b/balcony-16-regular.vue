<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ai2vbx6ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:balcony-16-regular" /></template>
<style>
.ai2vbx6ut {
  fill: currentColor;
  d: path("M9.756 1.013A2.5 2.5 0 0 1 12 3.5V6h2.5a.5.5 0 0 1 0 1H14v4.5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5V7h-.5a.5.5 0 0 1 0-1H4V3.5A2.5 2.5 0 0 1 6.5 1h3zM3.086 12c.207.582.761 1 1.414 1h7a1.5 1.5 0 0 0 1.413-1zM3 11h2.5V7H3zm7.5 0H13V7h-2.5zm-4 0h3V7h-3zm0-9A1.5 1.5 0 0 0 5 3.5V6h6V3.5a1.5 1.5 0 0 0-1.347-1.492L9.5 2z");
}

</style>
