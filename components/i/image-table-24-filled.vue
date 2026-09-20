<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8-3y-boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-table-24-filled" /></template>
<style>
.k8-3y-boy {
  fill: currentColor;
  d: path("M6.25 3h.25v3.5H3v-.25A3.25 3.25 0 0 1 6.25 3M3 16V8h3.5v8zm13-9.5H8V3h8zm1.5 0V3h.25A3.25 3.25 0 0 1 21 6.25v.25zm0 1.5H21v8h-3.5zm0 9.5H21v.25A3.25 3.25 0 0 1 17.75 21h-.25zm-1.5 0V21H8v-3.5zm-9.5 0V21h-.25A3.25 3.25 0 0 1 3 17.75v-.25zM8 15.068l2.409-2.409a2.25 2.25 0 0 1 3.182 0L16 15.068V8H8zM14 9a1 1 0 1 1 0 2a1 1 0 0 1 0-2m.81 7l-2.28-2.28a.75.75 0 0 0-1.06 0L9.19 16z");
}

</style>
