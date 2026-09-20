<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uc15whbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chart-bar-light" /></template>
<style>
.uc15whbeh {
  fill: currentColor;
  d: path("M224 202h-10V40a6 6 0 0 0-6-6h-56a6 6 0 0 0-6 6v42H96a6 6 0 0 0-6 6v42H48a6 6 0 0 0-6 6v66H32a6 6 0 0 0 0 12h192a6 6 0 0 0 0-12M158 46h44v156h-44Zm-56 48h44v108h-44Zm-48 48h36v60H54Z");
}

</style>
