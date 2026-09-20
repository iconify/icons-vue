<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tawbt38ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:hard-drive-16-filled" /></template>
<style>
.tawbt38ut {
  fill: currentColor;
  d: path("M12.5 8A1.5 1.5 0 0 1 14 9.5v1.002A1.5 1.5 0 0 1 12.5 12h-9A1.5 1.5 0 0 1 2 10.5v-1A1.5 1.5 0 0 1 3.5 8zm1.058-.766l-1.673-3.507V3.72A1.23 1.23 0 0 0 10.75 3h-5.5a1.23 1.23 0 0 0-1.134.72v.007L2.442 7.234A2.5 2.5 0 0 1 3.5 7h9c.378 0 .737.084 1.058.234M12 10.5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>
