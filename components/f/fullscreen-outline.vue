<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0cc0jbec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fullscreen-outline" /></template>
<style>
.u0cc0jbec {
  fill: currentColor;
  d: path("M4 20v-4.423h1V19h3.423v1zm11.596 0v-1h3.423v-3.423h1V20zM4 8.423V4h4.423v1H5v3.423zm15.02 0V5h-3.424V4h4.423v4.423z");
}

</style>
