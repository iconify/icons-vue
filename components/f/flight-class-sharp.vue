<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9r02ibyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:flight-class-sharp" /></template>
<style>
.g9r02ibyt {
  fill: currentColor;
  d: path("M12.616 12V5H17v7zM17 17H8.616L6 8.058V5h1v3l2.385 8H17zm-8.596 3v-1h8.577v1z");
}

</style>
