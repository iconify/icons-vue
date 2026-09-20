<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d-16ckbbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:apps-bullet-list-20-filled" /></template>
<style>
.d-16ckbbq {
  fill: currentColor;
  d: path("M8.646 3a2 2 0 0 0 0 1.5H5a.5.5 0 0 0-.5.5v4.25H15a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zM4.5 15a.5.5 0 0 0 .5.5h4.25v-4.75H4.5zm6.25.5H15a.5.5 0 0 0 .5-.5v-3.75a.5.5 0 0 0-.5-.5h-4.25zm-.25-9.25a1 1 0 1 1 0 2a1 1 0 0 1 0-2m6.75.25a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5zM10.5 2.75a1 1 0 1 1 0 2a1 1 0 0 1 0-2m6.75.25a.75.75 0 0 1 0 1.5h-3.5a.75.75 0 0 1 0-1.5z");
}

</style>
