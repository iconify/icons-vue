<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zk5_brj4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cube-focus-light" /></template>
<style>
.zk5_brj4v {
  fill: currentColor;
  d: path("M230 48v40a6 6 0 0 1-12 0V54h-34a6 6 0 0 1 0-12h40a6 6 0 0 1 6 6M72 202H38v-34a6 6 0 0 0-12 0v40a6 6 0 0 0 6 6h40a6 6 0 0 0 0-12m152-40a6 6 0 0 0-6 6v34h-34a6 6 0 0 0 0 12h40a6 6 0 0 0 6-6v-40a6 6 0 0 0-6-6M32 94a6 6 0 0 0 6-6V54h34a6 6 0 0 0 0-12H32a6 6 0 0 0-6 6v40a6 6 0 0 0 6 6m155 71.21l-56 32a6 6 0 0 1-6 0l-56-32a6 6 0 0 1-3-5.21V96a6 6 0 0 1 3-5.21l56-32a6 6 0 0 1 6 0l56 32a6 6 0 0 1 3 5.21v64a6 6 0 0 1-3 5.21M84.09 96L128 121.09L171.91 96L128 70.91ZM78 156.52l44 25.14v-50.18l-44-25.14Zm100 0v-50.18l-44 25.14v50.18Z");
}

</style>
