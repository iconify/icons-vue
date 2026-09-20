<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y0igtnbiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-add-16-filled" /></template>
<style>
.y0igtnbiy {
  fill: currentColor;
  d: path("M15 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V5H8.5a.5.5 0 0 0 0 1H10v1.5a.5.5 0 0 0 1 0V6h1.5a.5.5 0 0 0 0-1H11zm-.5 7.5c.9 0 1.75-.216 2.5-.6V13a2 2 0 0 1-2 2H3a2 2 0 0 1-2-2V8.337l5.763 3.103a.5.5 0 0 0 .474 0l1.411-.76c.579.207 1.202.32 1.852.32M3 5h2.022a5.5 5.5 0 0 0 2.522 5.14L7 10.431l-6-3.23V7a2 2 0 0 1 2-2");
}

</style>
