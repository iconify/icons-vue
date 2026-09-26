<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t9pdq7z0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:code-20-filled" /></template>
<style>
.t9pdq7z0v {
  fill: currentColor;
  d: path("M11.782 1.532a.75.75 0 0 1 1.435.436l-5 16.5a.75.75 0 0 1-1.435-.436zM4.946 4.995a.75.75 0 1 1 1.108 1.01L2.568 9.832a.25.25 0 0 0 0 .336l3.486 3.827a.75.75 0 0 1-1.108 1.01L1.46 11.179a1.75 1.75 0 0 1 0-2.358zm9.146-.056a.75.75 0 0 1 1.058.063l3.41 3.835a1.753 1.753 0 0 1 0 2.326l-3.41 3.835a.75.75 0 0 1-1.121-.996l3.41-3.836a.25.25 0 0 0 0-.332l-3.41-3.836a.75.75 0 0 1 .063-1.059");
}

</style>
