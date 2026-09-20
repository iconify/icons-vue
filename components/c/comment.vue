<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4v8pxhgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comment" /></template>
<style>
.a4v8pxhgw {
  fill: currentColor;
  d: path("M6 14h12v-2H6zm0-3h12V9H6zm0-3h12V6H6zM4 18q-.825 0-1.412-.587T2 16V4q0-.825.588-1.412T4 2h16q.825 0 1.413.588T22 4v18l-4-4z");
}

</style>
