<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y4p0d5b3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:laptop-dismiss-20-filled" /></template>
<style>
.y4p0d5b3f {
  fill: currentColor;
  d: path("M17.5 15a.5.5 0 0 1 0 1h-15a.5.5 0 0 1 0-1zM15 5a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-1.602A5.5 5.5 0 0 0 10.977 5zM5.5 1a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m1.854 2.646a.5.5 0 0 0-.708 0L5.5 4.793L4.354 3.646a.5.5 0 1 0-.708.708L4.793 5.5L3.646 6.646a.5.5 0 1 0 .708.708L5.5 6.207l1.146 1.147a.5.5 0 1 0 .708-.708L6.207 5.5l1.147-1.146a.5.5 0 0 0 0-.708");
}

</style>
