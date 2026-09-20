<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xwnmpgiov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-style-guide-16-filled" /></template>
<style>
.xwnmpgiov {
  fill: currentColor;
  d: path("M8.505 10.203a.7.7 0 0 1 .99 0l4.384 4.383A2.5 2.5 0 0 1 12.5 15h-7a2.5 2.5 0 0 1-1.379-.414zM12.5 3A2.5 2.5 0 0 1 15 5.5v7c0 .51-.152.984-.414 1.38l-4.384-4.385a1.7 1.7 0 0 0-2.404 0L3.414 13.88A2.5 2.5 0 0 1 3 12.5V10h2.5c.975 0 1.816-.56 2.229-1.374A2.5 2.5 0 0 0 9.877 6.79L10.893 3zm-7-1A1.5 1.5 0 0 1 7 3.5v4A1.5 1.5 0 0 1 5.5 9h-3A1.5 1.5 0 0 1 1 7.5v-4A1.5 1.5 0 0 1 2.5 2zM4.187 1a1.5 1.5 0 0 1 1.8-.945l2.897.776a1.5 1.5 0 0 1 1.06 1.837L8.91 6.533c-.13.482-.48.844-.914 1.01l.003-.043v-4a2.5 2.5 0 0 0-2.5-2.5zm7.311 4.5a1.002 1.002 0 1 0 0 2.004a1.002 1.002 0 0 0 0-2.004");
}

</style>
