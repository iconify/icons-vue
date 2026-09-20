<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ejfwr3-_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-16-regular" /></template>
<style>
.ejfwr3-_g {
  fill: currentColor;
  d: path("M11.25 4c.966 0 1.75.784 1.75 1.75v6.75a.5.5 0 0 1-1 0V7H8v4.25A1.75 1.75 0 0 1 6.25 13h-3.5A1.75 1.75 0 0 1 1 11.25v-5.5C1 4.784 1.784 4 2.75 4zM2 11.25c0 .414.336.75.75.75h3.5a.75.75 0 0 0 .75-.75V7H2zM11.251 2a3.75 3.75 0 0 1 3.75 3.75v4.75a.5.5 0 0 1-1 0V5.75A2.75 2.75 0 0 0 11.251 3h-8.08c.282-.59.882-1 1.58-1zM5.5 8a.5.5 0 0 1 0 1h-2a.5.5 0 0 1 0-1zM2.75 5a.75.75 0 0 0-.75.75V6h10v-.25a.75.75 0 0 0-.75-.75z");
}

</style>
