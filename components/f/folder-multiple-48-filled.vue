<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zapf_y6xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-multiple-48-filled" /></template>
<style>
.zapf_y6xz {
  fill: currentColor;
  d: path("M41.48 15.736a6.24 6.24 0 0 1 2.518 5.014v9.5c0 5.937-4.813 10.75-10.75 10.75h-18.5a6.24 6.24 0 0 1-5.014-2.518q.255.016.514.018h23a8.25 8.25 0 0 0 8.25-8.25v-14a8 8 0 0 0-.017-.514M33.25 10a6.25 6.25 0 0 1 6.25 6.25v14a6.25 6.25 0 0 1-6.25 6.25h-23A6.25 6.25 0 0 1 4 30.25V17h11.758a4.25 4.25 0 0 0 3.005-1.245L24.518 10zM15.758 5.5a4.25 4.25 0 0 1 3.005 1.245L21.5 9.482l-4.505 4.505a1.75 1.75 0 0 1-1.237.513H4v-2.75a6.25 6.25 0 0 1 6.25-6.25z");
}

</style>
