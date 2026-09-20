<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wp201xbao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-step-back-20-filled" /></template>
<style>
.wp201xbao {
  fill: currentColor;
  d: path("M7.851 3.146a.5.5 0 0 1 0 .707L4.706 7H10c2.932 0 5.593 1.64 6.936 4.043a.5.5 0 1 1-.872.488C14.894 9.439 12.564 8 10 8H4.707l3.144 3.145a.5.5 0 0 1-.707.707L3.161 7.867a.5.5 0 0 1-.014-.721l3.997-4a.5.5 0 0 1 .707 0M12 15a2 2 0 1 1-4 0a2 2 0 0 1 4 0");
}

</style>
