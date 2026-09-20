<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ab7xasouh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-shift-uppercase-20-filled" /></template>
<style>
.ab7xasouh {
  fill: currentColor;
  d: path("M11.144 2.53a1.5 1.5 0 0 0-2.288 0l-6.617 7.803a1 1 0 0 0 .763 1.647H6v3.017a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V11.98h2.996a1 1 0 0 0 .763-1.647zM6.5 17a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1z");
}

</style>
