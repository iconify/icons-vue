<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvvjq5b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flag-2-rounded" /></template>
<style>
.gvvjq5b1p {
  fill: currentColor;
  d: path("M7 13v8q0 .425-.288.713T6 22t-.712-.288T5 21V4q0-.425.288-.712T6 3h13.525q.275 0 .488.125t.337.325t.162.438t-.062.487L19 8l1.45 3.625q.1.25.063.488t-.163.437t-.337.325t-.488.125z");
}

</style>
