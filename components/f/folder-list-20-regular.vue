<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="do658kf0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-list-20-regular" /></template>
<style>
.do658kf0z {
  fill: currentColor;
  d: path("M4.5 3A2.5 2.5 0 0 0 2 5.5v9A2.5 2.5 0 0 0 4.5 17h6.585c.066-.186.168-.356.297-.5a1.5 1.5 0 0 1-.297-.5H4.5A1.5 1.5 0 0 1 3 14.5V8h4.086a1.5 1.5 0 0 0 1.06-.44L9.707 6H15.5A1.5 1.5 0 0 1 17 7.5V12h1V7.5A2.5 2.5 0 0 0 15.5 5H9.707L8.22 3.513A1.75 1.75 0 0 0 6.982 3zM3 5.5A1.5 1.5 0 0 1 4.5 4h2.482a.75.75 0 0 1 .53.22l1.28 1.28L7.44 6.854A.5.5 0 0 1 7.086 7H3zm9.5 7.5a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1zm0 2a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1zm-.5 2.5a.5.5 0 0 1 .5-.5h6a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5");
}

</style>
