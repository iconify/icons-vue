<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x80qa1b5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:contact-card-generic-16-filled" /></template>
<style>
.x80qa1b5c {
  fill: currentColor;
  d: path("M13.25 3c.966 0 1.75.784 1.75 1.75v6.5A1.75 1.75 0 0 1 13.25 13H2.75A1.75 1.75 0 0 1 1 11.25v-6.5C1 3.784 1.784 3 2.75 3zM5.5 6a2 2 0 1 0 0 4a2 2 0 0 0 0-4m4 3a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zm-4-2a1 1 0 1 1 0 2a1 1 0 0 1 0-2m4-1a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
