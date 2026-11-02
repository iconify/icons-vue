<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u--gstbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-open-fill" /></template>
<style>
.u--gstbfw {
  fill: currentColor;
  d: path("m3.127 7.713l5.318-3.545a6.41 6.41 0 0 1 7.11 0l5.318 3.545l-5.58 5.58c-.313.312-.825.707-1.293.707h-4c-.468 0-.98-.395-1.293-.707ZM19 22H5a3 3 0 0 1-3-3V9.414l5.293 5.293C8.008 15.422 8.961 16 10 16h4c1.039 0 1.992-.578 2.707-1.293L22 9.414V19a3 3 0 0 1-3 3");
}

</style>
