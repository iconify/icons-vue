<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gr-d04i3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:flag-2" /></template>
<style>
.gr-d04i3s {
  fill: currentColor;
  d: path("M5 22V3h16l-2 5l2 5H7v9z");
}

</style>
