<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yyiwi4vxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-style-guide-16-regular" /></template>
<style>
.yyiwi4vxc {
  fill: currentColor;
  d: path("M12.5 3A2.5 2.5 0 0 1 15 5.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 3 12.5V10h1v2.5c0 .232.053.451.146.647l3.652-3.652a1.7 1.7 0 0 1 2.404 0l3.652 3.652c.093-.196.146-.415.146-.647v-7A1.5 1.5 0 0 0 12.5 4h-1.875l.268-1zm-3.005 7.203a.7.7 0 0 0-.99 0l-3.651 3.65c.195.095.415.147.646.147h7a1.5 1.5 0 0 0 .646-.146zM5.5 2A1.5 1.5 0 0 1 7 3.5v4A1.5 1.5 0 0 1 5.5 9h-3A1.5 1.5 0 0 1 1 7.5v-4A1.5 1.5 0 0 1 2.5 2zM4.187 1a1.5 1.5 0 0 1 1.8-.946L8.884.83a1.5 1.5 0 0 1 1.06 1.838L8.91 6.532c-.13.482-.48.844-.914 1.01L8 7.5v-4A2.5 2.5 0 0 0 5.5 1zm7.311 4.5a1.002 1.002 0 1 1 0 2.004a1.002 1.002 0 0 1 0-2.004");
}

</style>
