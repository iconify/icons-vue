<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b3qdswbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-48-regular" /></template>
<style>
.b3qdswbpl {
  fill: currentColor;
  d: path("M41.48 15.736a6.24 6.24 0 0 1 2.518 5.014v9.5c0 5.937-4.813 10.75-10.75 10.75h-18.5a6.24 6.24 0 0 1-5.014-2.518q.255.016.514.018h23a8.25 8.25 0 0 0 8.25-8.25v-14a8 8 0 0 0-.017-.514M15.758 5.5a4.25 4.25 0 0 1 3.005 1.245L22.018 10H33.25a6.25 6.25 0 0 1 6.25 6.25v14a6.25 6.25 0 0 1-6.25 6.25h-23A6.25 6.25 0 0 1 4 30.25v-18.5a6.25 6.25 0 0 1 6.25-6.25zm3.005 10.255A4.25 4.25 0 0 1 15.758 17H6.5v13.25A3.75 3.75 0 0 0 10.25 34h23A3.75 3.75 0 0 0 37 30.25v-14a3.75 3.75 0 0 0-3.75-3.75H22.018zM10.25 8a3.75 3.75 0 0 0-3.75 3.75v2.75h9.258a1.75 1.75 0 0 0 1.237-.513l2.737-2.737l-2.737-2.737A1.75 1.75 0 0 0 15.758 8z");
}

</style>
