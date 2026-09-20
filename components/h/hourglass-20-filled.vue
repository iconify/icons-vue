<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bzfj5ybib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hourglass-20-filled" /></template>
<style>
.bzfj5ybib {
  fill: currentColor;
  d: path("M13.69 5.4c.2-.44.305-.917.31-1.4H6c.006.484.115.961.32 1.4c.208.45.515.847.9 1.16l1.82 1.52c.28.234.506.528.66.86c.16.33.241.693.24 1.06c.001.367-.08.73-.24 1.06a2.5 2.5 0 0 1-.66.86l-1.82 1.52a3.25 3.25 0 0 0-.9 1.16A3.4 3.4 0 0 0 6 16h8a3.5 3.5 0 0 0-.31-1.4a3.4 3.4 0 0 0-.91-1.16L11 11.91a2.45 2.45 0 0 1-.65-.85a2.4 2.4 0 0 1-.29-1.06a2.4 2.4 0 0 1 .29-1.06a2.45 2.45 0 0 1 .65-.85l1.78-1.53a3.4 3.4 0 0 0 .91-1.16");
}

</style>
