<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a4my6-t8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bookmark-flag-sharp" /></template>
<style>
.a4my6-t8y {
  fill: currentColor;
  d: path("M9.5 14H11v-3h4.5L14 9l1.5-2h-6zM5 21V3h14v18l-7-3z");
}

</style>
