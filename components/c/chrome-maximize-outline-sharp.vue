<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8j0ginoh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-maximize-outline-sharp" /></template>
<style>
.k8j0ginoh {
  fill: currentColor;
  d: path("M4 20V4h16v16Zm2-2h12V6H6ZM6 6v12Z");
}

</style>
