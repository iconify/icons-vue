<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lodb0-m3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-one-sharp" /></template>
<style>
.lodb0-m3w {
  fill: currentColor;
  d: path("M12.5 16.5h1v-9h-3v1h2zM20 20H4V4h16z");
}

</style>
