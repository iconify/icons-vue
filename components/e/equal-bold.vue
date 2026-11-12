<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z7j1l4gbc"/><path class="b6go78mri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:equal-bold" /></template>
<style>
.b6go78mri {
  fill: currentColor;
  d: path("M20 8.25C20.4142 8.25 20.75 8.58579 20.75 9C20.75 9.41421 20.4142 9.75 20 9.75H4C3.58579 9.75 3.25 9.41421 3.25 9C3.25 8.58579 3.58579 8.25 4 8.25H20Z");
}

.z7j1l4gbc {
  fill: currentColor;
  d: path("M20 14.25C20.4142 14.25 20.75 14.5858 20.75 15C20.75 15.4142 20.4142 15.75 20 15.75H4C3.58579 15.75 3.25 15.4142 3.25 15C3.25 14.5858 3.58579 14.25 4 14.25H20Z");
}

</style>
