<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="do125oyoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-square-24-regular" /></template>
<style>
.do125oyoz {
  fill: currentColor;
  d: path("M16.28 9.78a.75.75 0 0 0-1.06-1.06l-4.47 4.47l-1.474-1.474a.75.75 0 0 0-1.06 1.06l2.004 2.004a.75.75 0 0 0 1.06 0zM6.25 3A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3zM4.5 6.25c0-.966.784-1.75 1.75-1.75h11.5c.966 0 1.75.784 1.75 1.75v11.5a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
