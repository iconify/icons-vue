<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rd4if9rek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:church-thin" /></template>
<style>
.rd4if9rek {
  fill: currentColor;
  d: path("M226.06 148.57L188 125.74V104a4 4 0 0 0-2-3.47l-54-30.85V44h20a4 4 0 0 0 0-8h-20V16a4 4 0 0 0-8 0v20h-20a4 4 0 0 0 0 8h20v25.68l-54 30.85a4 4 0 0 0-2 3.47v21.74l-38.06 22.83A4 4 0 0 0 28 152v64a4 4 0 0 0 4 4h80a4 4 0 0 0 4-4v-48a12 12 0 0 1 24 0v48a4 4 0 0 0 4 4h80a4 4 0 0 0 4-4v-64a4 4 0 0 0-1.94-3.43M36 154.26l32-19.2V212H36Zm92-6.26a20 20 0 0 0-20 20v44H76V106.32l52-29.71l52 29.71V212h-32v-44a20 20 0 0 0-20-20m92 64h-32v-76.94l32 19.2Z");
}

</style>
