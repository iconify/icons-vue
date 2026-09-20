<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="owftpb1bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-right-48-filled" /></template>
<style>
.owftpb1bx {
  fill: currentColor;
  d: path("M15.94 39.31a1.5 1.5 0 0 1 0-2.12l13.439-13.44l-13.44-13.44a1.5 1.5 0 0 1 2.122-2.12l14.5 14.5a1.5 1.5 0 0 1 0 2.12l-14.5 14.5a1.5 1.5 0 0 1-2.122 0");
}

</style>
