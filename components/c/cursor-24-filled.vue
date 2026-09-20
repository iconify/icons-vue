<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yge1peb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-24-filled" /></template>
<style>
.yge1peb_p {
  fill: currentColor;
  d: path("M7.921 2.3C6.936 1.532 5.5 2.234 5.5 3.482v17.009c0 1.422 1.795 2.046 2.677.93l4.19-5.3a1.65 1.65 0 0 1 1.295-.626h6.852c1.428 0 2.049-1.808.921-2.684z");
}

</style>
