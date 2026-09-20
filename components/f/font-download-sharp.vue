<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3jelmydk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:font-download-sharp" /></template>
<style>
.f3jelmydk {
  fill: currentColor;
  d: path("M6.4 18h2.1l1.1-3.05h4.8L15.5 18h2.1L13.05 6h-2.1zm3.8-4.8l1.75-4.95h.1l1.75 4.95zM2 22V2h20v20z");
}

</style>
