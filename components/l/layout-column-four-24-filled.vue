<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b11cxkb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-four-24-filled" /></template>
<style>
.b11cxkb2r {
  fill: currentColor;
  d: path("M8 21h3.25V3H8zM6.5 3h-.25A3.25 3.25 0 0 0 3 6.25v11.5A3.25 3.25 0 0 0 6.25 21h.25zM16 21h-3.25V3H16zm1.5 0h.25A3.25 3.25 0 0 0 21 17.75V6.25A3.25 3.25 0 0 0 17.75 3h-.25z");
}

</style>
