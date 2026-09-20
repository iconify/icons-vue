<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vr7j70o3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-20-filled" /></template>
<style>
.vr7j70o3z {
  fill: currentColor;
  d: path("M12.042 7.5H12A1.5 1.5 0 0 0 10.5 9v2A2.5 2.5 0 0 1 8 13.5h-.042a3 3 0 1 1 0-1H8A1.5 1.5 0 0 0 9.5 11V9A2.5 2.5 0 0 1 12 6.5h.041a3 3 0 1 1 0 1");
}

</style>
