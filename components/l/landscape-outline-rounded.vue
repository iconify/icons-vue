<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_29wkskz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:landscape-outline-rounded" /></template>
<style>
.h_29wkskz {
  fill: currentColor;
  d: path("M3 18q-.625 0-.9-.55t.1-1.05l4-5.325q.15-.2.363-.3t.437-.1t.438.1t.362.3L11.5 16H19l-5-6.65l-1.7 2.25q-.3.4-.7.413t-.7-.213t-.4-.613t.2-.787l2.5-3.325q.15-.2.363-.3t.437-.1t.438.1t.362.3l7 9.325q.375.5.1 1.05T21 18zm8.5-2H19h-7.8h1.713zM5 16h4l-2-2.675zm0 0h4z");
}

</style>
