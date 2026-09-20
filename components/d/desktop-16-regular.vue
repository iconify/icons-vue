<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zj31cqbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-16-regular" /></template>
<style>
.zj31cqbyw {
  fill: currentColor;
  d: path("M4 2a2 2 0 0 0-2 2v5.997a2 2 0 0 0 2 2h2.005v1.011H4.506a.5.5 0 0 0 0 1h6.996a.5.5 0 1 0 0-1h-1.5v-1.01H12a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm5.003 9.997v1.011H7.005v-1.01zM3 4a1 1 0 0 1 1-1h8a1 1 0 0 1 1 1v5.997a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

</style>
