<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zgvnv35mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:item-compare-24-regular" /></template>
<style>
.zgvnv35mi {
  fill: currentColor;
  d: path("M12 2.5a.75.75 0 0 1 .75.75v17.5l-.004.077a.75.75 0 0 1-1.492 0l-.004-.077V3.25A.75.75 0 0 1 12 2.5M6.75 8A2.25 2.25 0 0 1 9 10.25v3.5A2.25 2.25 0 0 1 6.75 16h-3.5A2.25 2.25 0 0 1 1 13.75v-3.5A2.25 2.25 0 0 1 3.25 8zm14 0A2.25 2.25 0 0 1 23 10.25v3.5A2.25 2.25 0 0 1 20.75 16h-3.5A2.25 2.25 0 0 1 15 13.75v-3.5A2.25 2.25 0 0 1 17.25 8zM3.25 9.5a.75.75 0 0 0-.75.75v3.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75v-3.5a.75.75 0 0 0-.75-.75zm14 0a.75.75 0 0 0-.75.75v3.5c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75v-3.5a.75.75 0 0 0-.75-.75z");
}

</style>
