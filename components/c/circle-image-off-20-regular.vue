<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjy-c_b7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-off-20-regular" /></template>
<style>
.xjy-c_b7b {
  fill: currentColor;
  d: path("M2.146 2.146a.5.5 0 0 1 .708 0l15 15a.5.5 0 0 1-.707.707l-.27-.268A2.5 2.5 0 0 1 15.5 18h-5A2.5 2.5 0 0 1 8 15.5v-5c0-.51.152-.984.414-1.379L4.13 4.836A5 5 0 0 0 7 12.899v1.016a6 6 0 0 1-3.581-9.789L2.146 2.854a.5.5 0 0 1 0-.708m11.561 12.268a1 1 0 0 0-1.414 0l-2.44 2.44c.196.093.415.146.647.146h5a1.5 1.5 0 0 0 .646-.146zm-4.56-4.56A1.5 1.5 0 0 0 9 10.5v5c0 .232.053.45.146.646l2.44-2.439c.258-.258.569-.43.897-.517zM15.5 8a2.5 2.5 0 0 1 2.5 2.5v5c0 .12-.012.236-.028.35L17 14.88V10.5A1.5 1.5 0 0 0 15.5 9h-4.379l-.973-.973q.172-.025.352-.027zm-.5 2a1 1 0 1 1 0 2a1 1 0 0 1 0-2M8 2a6 6 0 0 1 5.915 5h-1.016a5 5 0 0 0-7.211-3.434l-.736-.735A5.97 5.97 0 0 1 8 2");
}

</style>
