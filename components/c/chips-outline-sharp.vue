<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6ufwm74y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chips-outline-sharp" /></template>
<style>
.j6ufwm74y {
  fill: currentColor;
  d: path("M7.5 12.5h9v-1h-9zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
