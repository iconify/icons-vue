<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sba0z8bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fullscreen-exit-outline-sharp" /></template>
<style>
.sba0z8bdk {
  fill: currentColor;
  d: path("M7.423 20v-3.423H4v-1h4.423V20zm8.173 0v-4.423h4.423v1h-3.423V20zM4 8.423v-1h3.423V4h1v4.423zm11.596 0V4h1v3.423h3.423v1z");
}

</style>
