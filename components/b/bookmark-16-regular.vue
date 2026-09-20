<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f6klmpbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bookmark-16-regular" /></template>
<style>
.f6klmpbrh {
  fill: currentColor;
  d: path("M3.78 13.918a.5.5 0 0 1-.778-.416V4.01a2 2 0 0 1 1.996-2l6-.011a2 2 0 0 1 2.004 1.996v9.506a.5.5 0 0 1-.778.416l-4.222-2.82zM12.002 4l-.007-.118A1 1 0 0 0 11 3l-6 .01a1 1 0 0 0-.998 1v8.557l3.722-2.485a.5.5 0 0 1 .556 0l3.722 2.485z");
}

</style>
