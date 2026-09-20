<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="db2lo3b9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:drink-beer-24-filled" /></template>
<style>
.db2lo3b9n {
  fill: currentColor;
  d: path("M7.25 2A3.25 3.25 0 0 0 4 5.25v14.5A2.25 2.25 0 0 0 6.25 22h9a2.25 2.25 0 0 0 2.25-2.25V18h1.25A3.25 3.25 0 0 0 22 14.75v-5.5A3.25 3.25 0 0 0 18.75 6H17.5v-.75A3.25 3.25 0 0 0 14.25 2zm11.5 14.5H17.5v-9h1.25c.966 0 1.75.784 1.75 1.75v5.5a1.75 1.75 0 0 1-1.75 1.75M16 6H5.5v-.75c0-.966.784-1.75 1.75-1.75h7c.966 0 1.75.784 1.75 1.75zm-7.5 4v7A.75.75 0 0 1 7 17v-7a.75.75 0 0 1 1.5 0m3 0v7a.75.75 0 0 1-1.5 0v-7a.75.75 0 0 1 1.5 0m3 0v7a.75.75 0 0 1-1.5 0v-7a.75.75 0 0 1 1.5 0");
}

</style>
