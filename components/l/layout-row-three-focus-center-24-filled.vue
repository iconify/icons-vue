<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoa742adx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-row-three-focus-center-24-filled" /></template>
<style>
.aoa742adx {
  fill: currentColor;
  d: path("M3 17.75A3.25 3.25 0 0 0 6.25 21h11.5A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3H6.25A3.25 3.25 0 0 0 3 6.25zm3.25 1.75a1.75 1.75 0 0 1-1.75-1.75V15h15v2.75a1.75 1.75 0 0 1-1.75 1.75zM19.5 9h-15V6.25c0-.966.784-1.75 1.75-1.75h11.5c.966 0 1.75.784 1.75 1.75z");
}

</style>
