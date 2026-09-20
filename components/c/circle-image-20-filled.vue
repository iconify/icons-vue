<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kdf5jc56g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-20-filled" /></template>
<style>
.kdf5jc56g {
  fill: currentColor;
  d: path("M12.293 14.414a1 1 0 0 1 1.414 0l3.172 3.172c-.395.262-.87.414-1.379.414h-5c-.51 0-.984-.152-1.379-.414zM15.5 8a2.5 2.5 0 0 1 2.5 2.5v5c0 .51-.152.984-.414 1.379l-3.172-3.172a2 2 0 0 0-2.828 0l-3.172 3.172A2.5 2.5 0 0 1 8 15.5v-5A2.5 2.5 0 0 1 10.5 8zM8 2a6 6 0 0 1 5.915 5H10.5A3.5 3.5 0 0 0 7 10.5v3.415A6 6 0 0 1 8 2m7 8a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
